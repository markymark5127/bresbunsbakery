# Bre's Buns Bakery

A responsive, mobile-first static website for **Bre's Buns**, a local cinnamon roll bakery in York, Pennsylvania.

## Included

- Custom pink/white/cinnamon visual theme
- Responsive desktop, tablet, and mobile layouts
- Branded transparent logo + wide header art
- Menu cards with editable prices
- Interactive "build your box" cart
- Copyable order-request summary
- Pickup section with Google Maps directions
- Custom domain file for `bresbunsbakery.com`
- GitHub Pages-ready static files

## Local preview

Open `index.html` directly, or run any static file server from the repository root.

## Editing the menu

Menu items live in `index.html`. Each `.bun-card` has `data-item` and `data-price` values used by the cart in `script.js`.

## Ordering

The current site intentionally does not send payment or personal information anywhere. The order builder copies a formatted order request to the shopper's clipboard. It can later be connected to Square, Shopify, Stripe, Formspree, an email form, or another ordering platform.

## Pickup address

135 Cedar Run Dr  
York, PA 17404
