# kolsu-website — Claude Context

Snel-startbestand voor Claude aan het begin van elke sessie.

## Wat is dit?
Statische website voor Kolsu. Pure HTML/CSS/JS — geen build step, geen framework.

## Stack
- HTML5
- CSS (vanilla)
- JavaScript (vanilla, indien nodig)
- Assets en images in `assets/` en `images/`

## Key files
```
index.html      — hoofdpagina
assets/         — CSS, JS, fonts, icons
images/         — foto's en grafisch materiaal
README.md       — projectbeschrijving
```

## Lokaal draaien
```bash
# Optie A: Python
python3 -m http.server 8000

# Optie B: VS Code Live Server extensie
# Rechtermuisknop op index.html → "Open with Live Server"
```

## Conventies
- Semantische HTML (gebruik `<main>`, `<section>`, `<nav>` etc.)
- CSS direct in `assets/` — geen preprocessor zoals Sass
- Beeldnamen kleine letters met streepjes: `logo-kolsu.png`, niet `LogoKolsu.png`
- Alle tekst in het Nederlands tenzij expliciet anders

## Let op
- Geen build artifacts — wat je schrijft is wat gedeployed wordt.
- Check responsive gedrag op mobile (de site wordt waarschijnlijk vooral mobiel bekeken).
- Compress images vóór committen (gebruik tinypng.com of vergelijkbaar).
