# TRS Gadgets

A single-file gadget shop website: public storefront (products, categories, cart, checkout with delivery-area based charges and bKash/Bank/COD payment) plus a hidden admin panel (products, categories, orders, a built-in invoice/memo generator, multi-admin accounts, and branding/contact settings).

## How it works

Everything lives in one self-contained `index.html` — no build step. Open it directly in a browser, or serve it via GitHub Pages.

**Admin access:** click the footer copyright line 3 times to reveal the admin login. Default login is `admin` / `123` — change this immediately from the admin panel's Admin Users section once you're in.

## Status

This version stores its data in the browser's local storage (per-device). A Supabase-backed version (shared, persistent database) is in progress.
