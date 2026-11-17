# KVIST — Furniture & Home Objects E-commerce

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/kvist-furniture-commerce/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A runnable, responsive vanilla HTML/CSS/JavaScript recreation of the supplied 23.37-second screen recording.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.

No npm install or build step is required. Optional:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## Screens and interactions recreated from the recording
- KVIST storefront header and navigation: Shop all, Seating, Lighting, Textiles, Ceramics, account and bag.
- Home hero: “Calm objects for slow homes.”, Bolle Lounge Chair feature, lighting tile, delivery tile and social proof.
- “This week’s favourites” product grid with category filters.
- Brand manifesto and newsletter sign-up.
- Shop category listing and product cards.
- Product detail page (Linne Table Lamp): product description, finish swatches, quantity stepper, add to bag, shipping/30-night trial/FSC information, Details / Dimensions / Care tabs.
- Bag drawer with item quantity controls, remove item and subtotal.
- Sign-in / create-account panel with demo admin entry.
- Checkout: delivery address, Standard / Express delivery, Pay on delivery / Bank transfer, order summary and confirmation.
- Admin dashboard: Overview metrics, 30-day revenue chart, live orders, sales by category, Today summary.
- Admin Orders page: All / Paid / Packing / Shipped / Delivered filters, search, order status actions.
- Admin Products, Categories and Storefront sections.

## Source extraction
The supplied recording shows the rendered KVIST website and several user flows, but does not show a source-code editor or readable HTML/CSS/JS source. Therefore, no original source code can be transcribed verbatim from this recording. The project is reconstructed from the visible UI and interactions.

## Demo-only limitations
- Product records, pricing, reviews, order data and admin analytics are representative local demo data based on visible values.
- Bag and checkout are frontend-only; no real payment is collected.
- Sign-in, account creation, order status changes and newsletter are demo interactions. No backend, authentication, email provider, inventory or order database is connected.
- Product photography loads from Unsplash and requires an internet connection.
- Bag contents are held in page memory and reset on refresh.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
