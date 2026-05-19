# SN20 Breeding Ground — Prototype

A clickable front-end prototype of the SN20 Breeding Ground website.
Static HTML/CSS/JS — no build step, no backend.

## Pages
- `index.html` — landing page (home)
- `for-teams.html` — founder decision page: why apply, the timeline, the buyback
- `for-backers.html` — backer decision page: the two ways to back, how a position pays
- `partners.html` — Core Partners & Strategic Partners; Strategic Partner intake form
- `flywheel.html` — the flywheel / 4-party model + interactive calculator
- `architecture.html` — how the program is built, on Bittensor primitives
- `incubations.html` — Intake 01 grid (8 teams)
- `team-helix.html`, `team-verdict.html`, `team-cropmind.html` — team dashboards
- `apply.html` — team application form

## Navigation
Every page shares one canonical nav:
`/home · /how-it-works · /for-teams · /for-backers · /partners · /intake-01 · [Apply]`
- `/how-it-works` is an anchor link to `index.html#how` (the cycle section).
- `flywheel.html` and `architecture.html` are linked from within pages and the
  footer, not from the top nav.

## Before publishing — TODO
- `partners.html` uses a placeholder email `partners@sn20.example` for the Strategic
  Partner intake (in the form's `PARTNER_EMAIL` constant and the sidebar mail link).
  Replace it with the real address.
- Core / Strategic partner cards on `partners.html` are shown by role and marked
  "In discussion" — swap in named partners as agreements are signed.

## What is SIMULATED (needs real integration by the dev team)
- Wallet connect (team dashboards) — fake connect flow, no real wallet
- "Lock TAO" crowdloan flow — fake confirm/success, no real transaction
- Apply form submission — fake confirmation, no data is sent or stored
- Strategic Partner intake (`partners.html`) — builds a mailto, no backend
- Video upload on the apply page — UI only, no file is uploaded
- All teams, figures, and metrics are illustrative sample data

## What is REAL
- All layout, styling, copy, navigation, responsive behavior
- The flywheel calculator math (runs live in-browser)
- Form interactions, filters, progress tracking

## Hosting
Deploys as a static site on Vercel with zero configuration.
