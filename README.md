# Tom Kamphuis — Positioneringssite

Statische, dependency-vrije site (HTML/CSS/JS, geen build-stap) gebaseerd op je
persoonlijk ontwikkelplan: visie, track record, ervaring en het profiel van je
ideale volgende rol.

## Lokaal bekijken

```
python -m http.server 8000
```

Open daarna `http://localhost:8000`.

## Hosten

Werkt direct op elke statische host, zonder build-stap:

- **GitHub Pages**: repo aanmaken, deze bestanden pushen, Pages aanzetten op de `main`-branch.
- **Netlify / Vercel**: map slepen naar hun dashboard, of repo koppelen.

## Bestanden

- `index.html` — alle inhoud
- `css/styles.css` — styling (licht/donker thema automatisch via systeeminstelling)
- `js/main.js` — mobiel menu + jaartal in footer
- `assets/favicon.svg` — favicon
