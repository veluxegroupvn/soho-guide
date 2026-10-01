# Veluxe Stay — SOHO Residences Guest Guide

## What's in here
- `index.html` — the full guest guide (self-contained, images already embedded as base64, so this one file is all GitHub Pages needs)
- `images/qr_soho.png` — QR code encoding https://soho.veluxestay.com, VS mark in black, brand bronze modules
- `images/logo-horizontal.png` — Artboard_24, the real logo lockup used in the guide header
- `images/logo-vertical.png` — Artboard_2, the stacked lockup for the printed card / square uses
- `images/vs-icon-bronze.png` / `vs-icon-black.png` — icon-only crops, no wordmark, used as the QR center mark

## Deploy status
Published at https://soho.veluxestay.com through the `veluxegroupvn/soho-guide` GitHub repository, using `main` and the repository root.

The navigation redesign dated 2026-10-01 is included in main. GitHub Pages publishes changes automatically after a successful push.

## To edit
Open `index.html`, search for `const CONFIG` near the bottom. wifiName, hostPhone,
checkIn/checkOut, and the exchange/spa links all live there. Everything else is
plain HTML further up the file, organized by <section id="..."> blocks.

## Source of truth for fees
Fees follow the internal SOP (Google Doc), not the printed card, where the two
ever disagree. Late check-out, luggage storage, mid-stay cleaning tiers were
last reconciled to the SOP on this date.

## Still to build
- Printed card redesign to match the SOP's late check-out numbers

Rivergate guide is done, see `../veluxe-rivergate-guide/`.

## Navigation redesign, 2026-10-01

The opening shows WiFi, the driver address, stay times and host contact. A sticky “Find something” menu replaces the 13 card contents grid. Six groups provide short descriptions and direct links to individual answers. Links open the relevant accordion automatically, including when a guest opens a URL with a fragment. Escape closes the menu.

Luggage has its own answer and retains the property's existing policy. Rubbish photos are preserved and shown on request. Nearby food and Grab delivery appear first in the food section. Attraction and mall durations explicitly say “by car”. All other local durations retain each building's own starting point.

Browser validation covers all three guides at widths of 320, 390, 430, 768 and 1280 pixels, all 29 unique menu destinations, keyboard dismissal, copy buttons, photo preservation and existing extras and late check out prices.
