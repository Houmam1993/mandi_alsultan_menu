# Mandi Al Sultan — Online Menu

Static menu page for Mandi Al Sultan Restaurant (Badr Street, Al Nuaimiya 3, Ajman).
Customers browse dishes and send their order straight to WhatsApp.

Hosted on GitHub Pages. No build step: every change pushed to `main` goes live in about a minute.

## Files
- `index.html` — the whole page (design, text, dishes, prices)
- `images/` — dish photos (960×720 JPG), logo and icons
- `.nojekyll` — tells GitHub Pages to serve files as-is
- `CNAME` — created by GitHub when the custom domain is set (do not delete)

## Common edits (all inside `index.html`)
- **Phone numbers:** `PHONE_CALL` and `PHONE_WA` near the top of the `<script>`.
- **Prices:** find the dish in `DISHES` and change `price:` (or the `price` inside `opts` for sizes).
- **Price on request:** `price:null`.
- **Add a dish:** copy an existing dish line, give it a new `id`, set `cat`, names, description, price and `img`.
- **Add an offer:** add a dish with `cat:"offers"` (optional `was:` for the crossed-out old price).
  The Offers tab appears automatically once one offer exists.
- **Photos:** add a 960×720 JPG to `images/` and point `img:` to it.
