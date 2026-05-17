# SN20 Breeding Ground — Prototype

A clickable front-end prototype of the SN20 Breeding Ground website.
Static HTML/CSS/JS — no build step, no backend.

## Pages
- `index.html` — landing page (home)
- `flywheel.html` — the flywheel / 4-party model + interactive calculator
- `incubations.html` — Cohort 01 grid (8 teams)
- `team-helix.html`, `team-verdict.html`, `team-cropmind.html` — team dashboards
- `apply.html` — team application form

## What is SIMULATED (needs real integration by the dev team)
- Wallet connect (team dashboards) — fake connect flow, no real wallet
- "Lock TAO" crowdloan flow — fake confirm/success, no real transaction
- Apply form submission — fake confirmation, no data is sent or stored
- Video upload on the apply page — UI only, no file is uploaded
- All teams, figures, and metrics are illustrative sample data

## What is REAL
- All layout, styling, copy, navigation, responsive behavior
- The flywheel calculator math (runs live in-browser)
- Form interactions, filters, progress tracking

## Hosting
Deploys as a static site on Vercel with zero configuration.
