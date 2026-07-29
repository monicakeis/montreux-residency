# The Montreux Residency

Static landing page for residency.eastwoodmontreux.ch

## Deploy (GitHub Pages)
1. Push these files to the repo root of a branch (e.g. `main`).
2. Settings > Pages > Source: Deploy from a branch > `main` / `/ (root)`.
3. Add a `CNAME` file containing `residency.eastwoodmontreux.ch` and point a DNS CNAME record at `<org>.github.io`.

## Contents
- `index.html` — the whole page (inline CSS + JS, no build step)
- `assets/em-logo-white-2.png` — logo, nav + footer
- `assets/photos/` — hero photograph and the 30 strip photographs

## Notes
- Typeform `OLHy2RO6` is embedded inline and receives `school`, `version` and `source` URL parameters as hidden fields, e.g.
  `https://residency.eastwoodmontreux.ch/?school=nova&version=a&source=whatsapp`
- Fonts load from Google Fonts (Inter, Bodoni Moda).
