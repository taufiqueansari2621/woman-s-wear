# Zikra Arts

A responsive commerce prototype for a premium Indian womenswear label. Built as a fast, dependency-free HTML/CSS/JavaScript experience.

## Included

- Editorial homepage, rotating offer bar, mega navigation, collection filters and sorting
- A 36-piece realistic catalog with ₹ pricing, discounts, variants, ratings and reviews
- Predictive search, accessible product quick view and required size selection
- Persistent wishlist and shopping bag with quantity controls and live totals
- Complimentary-shipping progress, account demo and safe checkout handoff
- Six-stage made-to-measure designer with live configuration and pricing
- Information and shipping checkout handoff (payment-provider UI intentionally does not collect card data)
- Responsive layouts from 320px phones through desktop
- Original AI-generated campaign assets optimized to WebP
- Open Graph metadata, `robots.txt`, and `sitemap.xml` starter

This repository is currently a front-end commerce prototype. Real authentication, inventory, taxation, orders, payment processing, admin RBAC, and database persistence require a trusted backend and production credentials; the UI does not pretend to process a payment without them.

## Run

Open `index.html` directly or run a local server:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

Production deployment: <https://woman-s-wear.valorled-store.workers.dev>
