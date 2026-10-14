# Toveli Restaurant Admin — HTML/CSS/JS Demo

This is a standalone front-end reproduction of the approved Toveli Restaurant Overview design, using Manrope, navy #101f3a, warm ivory #fcfaf7, and sand #e6b789.

## Open

Open `index.html` in a modern browser. If your browser blocks local-file operations, serve the folder with `python -m http.server 8000` and open http://localhost:8000/.

## Files

- `index.html` — layout structure and semantic HTML.
- `styles.css` — responsive styling, typography, spacing, and component system.
- `app.js` — page rendering, sample data, basic interaction logic.
- `assets/` — food and restaurant thumbnail crops from the approved generated reference image.

## Implemented interactions

Overview navigation and shortcut cards; KPI drill-down; searchable and filterable Menu page; modal item creation/editing; inline price editing; immediate availability toggle with Undo; draft publication selection; Specials page and editor; date-range and ranking controls in Analytics; notifications and recent activity; responsive navigation; sample data stored using `localStorage`.

## Scope limitations

This is a functional **front-end demonstration**, not a production restaurant dashboard. Metrics and activity are illustrative. No server, authentication, database, actual live-menu publishing, email/password management, file uploads, tenant isolation, or real analytics collection is connected. The Menu structure workspace is preliminary, not a complete hierarchy editor. All data is local to the current browser.

The supplied restaurant management specification also describes additional validation, allergen, nutrition, and review-preview workflows that require further implementation before production use.
