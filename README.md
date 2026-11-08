# e-plantShopping

**Paradise Nursery** – an online plant shop built with React, Redux Toolkit and Vite.

## Overview

The e-plantShopping application lets users browse and buy houseplants:

- **Landing page** – company name, background image, a short About Us section and a "Get Started" button.
- **Product listing page** – plants grouped by category (Air Purifying, Aromatic, Insect Repellent, Medicinal, Low Maintenance), each with image, name, description, price and an "Add to Cart" button that becomes disabled ("Added to Cart") once clicked.
- **Shopping cart page** – shows each plant's quantity and subtotal, total cart amount, increment/decrement and delete buttons, Continue Shopping and Checkout.
- **Global state** – the cart is managed with Redux (`CartSlice.jsx`, `store.js`); the cart icon in the navbar shows the total number of items.

## Run locally

```bash
npm install
npm run dev
```

## Deploy

```bash
npm run deploy
```

Live site: https://huynguyen736.github.io/e-plantShopping/
