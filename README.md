# FreshMart — Grocery Store (Demo Storefront)

A clean, bright online grocery store inspired by the TikTok explainer "Why THIS design sells more groceries" — rebuilt full-frame with the design's conversion tricks baked in: category filtering, honest per-unit pricing, weekly deals with a real countdown, and a free-delivery progress bar.

## What's inside
- **Hero** — "Fresh Fruits & Vegetables. Delivered Daily." with produce photography and floating product/order cards
- **Popular Categories** — 5 photo category cards (Produce, Bakery, Dairy & Eggs, Meat & Fish, Pantry) that actually filter the shop
- **Shop grid** — 16 products with category badges, sale badges, pack sizes and **per-unit pricing** under every price
- **Search** — live search in the header filters products as you type
- **Weekly Deals** — 3 marked-down products with a **real countdown timer** to Sunday 23:59, ticking every second
- **Cart drawer** — add/remove, quantity steppers, subtotal, delivery fee logic, and a **free-delivery progress bar** ($50 threshold — fee drops to FREE when you cross it)
- **Checkout** — success state with order number and delivery-slot message
- **Footer** — full store info: address, opening hours, phone and email
- **Extras** — toast notifications, scroll-reveal animations, fully responsive

## Run it
Open `index.html` in any browser. No build step, no dependencies beyond Google Fonts.

## Make it yours (buyer guide)
- **Products:** edit the `PRODUCTS` array — name, category, price, `old` price (adds a sale badge + deals-section entry), pack size, per-unit text, image
- **Categories:** edit `CATEGORIES` and the filter pills to match your aisles
- **Free delivery:** change `FREE_AT` and `DELIVERY_FEE` constants at the top of the script
- **Photos:** replace files in `images/` (Unsplash placeholders — use your own photography before launch)
- **Brand:** rename FreshMart, adjust the green palette via `:root` variables, update store details in the footer
- **Checkout:** the demo checkout is a front-end success state; connect the `checkoutBtn` handler to your payment/delivery provider for live orders

## Files
- `index.html` — the entire site (embedded CSS + JS)
- `images/` — 17 product/store photos
- `README.md` — this file
