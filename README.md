# Veluxe Stay — SOHO Residences Guest Guide

## What's in here
- `index.html` — the full guest guide (self-contained, images already embedded as base64, so this one file is all GitHub Pages needs)
- `images/qr_soho.png` — QR code encoding https://soho.veluxestay.com, VS mark in black, brand bronze modules
- `images/logo-horizontal.png` — Artboard_24, the real logo lockup used in the guide header
- `images/logo-vertical.png` — Artboard_2, the stacked lockup for the printed card / square uses
- `images/vs-icon-bronze.png` / `vs-icon-black.png` — icon-only crops, no wordmark, used as the QR center mark

## Deploy status
Not yet live. Steps still needed:
1. Create GitHub repo under the `veluxegroupvn` account, upload `index.html`
2. Settings → Pages → Deploy from main / root
3. Settings → Pages → Custom domain → `soho.veluxestay.com`
4. GoDaddy DNS → CNAME record: Name `soho`, Value `veluxegroupvn.github.io`

## To edit
Open `index.html`, search for `const CONFIG` near the bottom. wifiName, hostPhone,
checkIn/checkOut, and the exchange/spa links all live there. Everything else is
plain HTML further up the file, organized by <section id="..."> blocks.

## Source of truth for fees
Fees follow the internal SOP (Google Doc), not the printed card, where the two
ever disagree. Late check-out, luggage storage, mid-stay cleaning tiers were
last reconciled to the SOP on this date.

## Still to build
- Rivergate guide (copy this file, edit CONFIG + the two BUILDING-SPECIFIC blocks)
- Tresor guide (same)
- Printed card redesign to match the SOP's late check-out numbers
