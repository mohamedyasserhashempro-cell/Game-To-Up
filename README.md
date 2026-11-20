# Game-To-Up | Demo Storefront

**Game-To-Up** is an Arabic, right-to-left storefront UI concept for gaming top-ups and digital gift cards. This repository contains the demonstration project and is intended for portfolio review.

> **Demo only:** no real payments, top-ups, customer orders, or account-data processing are connected. Do not enter real personal, payment, or game-account details.

## What is included

- Responsive Arabic RTL storefront layout
- Product and package browsing
- SAR, SDG, and USD display switching
- Demo order modal and tracking-page layout
- Tailwind CSS 4 and Vite build setup

## Run locally

Requirements: Node.js 20.19+ (Node 22.12 is configured for deployment).

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

The generated static site is written to `dist/`. Netlify is configured through `netlify.toml` to run `npm run build` and publish `dist`.

## Security scope

The public demo disables the owner dashboard, removes the prototype PIN/password flow, clears old local order records, and does not create or persist new orders. Payment method names are illustrative only. Browser storage is local to each visitor and is not a shared database.

A production store requires server-side authentication and authorization, a database, server-validated pricing and order state, and a real payment-provider integration with verified payment callbacks. Never put payment secrets or private API keys in frontend code.

## Rights

All rights reserved. This is a portfolio demonstration; no permission to reuse, modify, or redistribute the source is granted without prior written permission. See `LICENSE`.
