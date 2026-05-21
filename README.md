# Mount Edgecombe Country Club — Project Dashboard

Single-page estimate dashboard for ME 421 — Alterations and Additions to Main Clubhouse Restaurant/Dining Area.

- **Client:** Mount Edgecombe Country Club Estate
- **Contractor:** DF Strange Builders
- **GBA:** 292 m²
- **Base Date:** May 2026
- **Sub-Total (ex VAT):** R 2,371,244.49
- **Total (incl VAT):** R 2,726,931.16

## Stack

Static single-file HTML — Vercel-hosted. Chart.js for the cost-split doughnut. No backend, no auth — public estimate view.

## Assets

Drop client and contractor logos at:

- `assets/client-logo.png` — Mount Edgecombe Country Club Estate crest
- `assets/contractor-logo.png` — DF Strange Builders mark

If a logo file is missing the header falls back gracefully (hides the image element).

## Deploy

```bash
git add .
git commit -m "Update dashboard"
git push
```

Vercel auto-deploys on push to `master`.
