# Anilam ERP — Hotel & Multi-Store Restaurant POS

A single-file, client-side ERP dashboard for hotel room management and restaurant POS, built with HTML, Tailwind CSS, and Chart.js.

## Features

- Revenue dashboard with live charts (room bookings vs. restaurant POS)
- Room management & guest check-in registry
- Restaurant POS with categorized menu grid
- Sales reports & printable receipts
- Menu/product management
- Loyalty & referral points tracking
- Promotions/offers broadcast
- Multi-store switching
- JSON backup & restore

## Live Demo

Once GitHub Pages is enabled for this repo (Settings → Pages → Deploy from branch → `main` / root), your app will be live at:

```
https://<your-username>.github.io/<repo-name>/
```

## Running Locally

Just open `index.html` in any modern browser — no build step, no server required.

## Data Persistence

**Important:** All data (bookings, sales, products, etc.) is held in browser memory only and is lost on page refresh. Use **Backup & Restore → Backup Now** to export a JSON snapshot, and **Restore** to reload it in a future session.

## Tech Stack

- Tailwind CSS (via CDN)
- Chart.js (via CDN)
- Font Awesome (via CDN)
- Vanilla JavaScript — no framework, no build tools
