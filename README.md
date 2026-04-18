# kolsu-website

Statische website voor Kolsu. Pure HTML/CSS/JS — geen build step, geen framework.

## Structuur

```
index.html     Hoofdpagina
assets/        CSS, JS, fonts, icons
images/        Beeldmateriaal
```

## Lokaal draaien

```bash
# Simpele Python server
python3 -m http.server 8000
# → http://localhost:8000
```

Of in VS Code: rechtermuisknop op `index.html` → **Open with Live Server** (Live Server extensie nodig).

## Deploy

TODO: vul hier in waar de site gehost wordt en hoe een deploy gedaan wordt.

## Conventies

- Semantische HTML (`<main>`, `<section>`, `<nav>`)
- Bestandsnamen: kleine letters met streepjes
- Responsive design — test op mobile
- Images comprimeren vóór committen

## Licentie

Private. Intellectueel eigendom van RNDX Labs B.V.
