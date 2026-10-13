# InCheck 360 — Completion Dashboard (Static Demo)

A self-contained, responsive completion reporting dashboard with fictional demonstration records. No backend, API keys, Supabase, authentication, npm installation, or build process required.

## Quick start

Open `index.html` in a modern browser. The full dashboard works locally without internet access.

## Deploy to GitHub Pages

1. Create a new GitHub repository, for example `incheck-completion-dashboard`.
2. Upload `index.html`, `styles.css`, `data.js`, `app.js` and this README to the repository root.
3. Under Settings → Pages, select Deploy from a branch, then `main` and `/ (root)`.
4. Save and visit the URL published by GitHub Pages.

## Included

- Responsive dashboard and dark mode
- KPI cards, completion trend, outcome donut, brand comparison, lowest-performing locations
- Period, brand, location, status and free-text filters
- Clickable brand breakdown, sort and pagination
- CSV export of filtered records and browser print / Save as PDF (A4 landscape)
- Deterministic example records in `data.js`

## Edit demo data

Edit `DEMO_BRANDS`, `DEMO_CHECKLISTS` and the record generator in `data.js`.

**Note:** This is a rebuilt demonstration package, not a byte-for-byte recovery of the original project. The data is fictional and must not be used for operational decision-making.
