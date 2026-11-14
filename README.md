# Kopi Kiwari Tikulon

Static ordering storefront for Vercel. It has no database and sends the formatted order to WhatsApp.

## Run locally

```bash
npx serve .
```

Or open `index.html` directly in a browser. `localStorage` keeps the cart on the same device.

## Before publishing

1. Open `app.js` and replace `WHATSAPP_NUMBER` with the business number in international format, without `+`, spaces, or dashes.
2. Confirm prices and product names against the latest menu.
3. Replace abstract cup visuals with real product photos when available.
4. Set the Vercel project root to this directory, or deploy the directory directly.

## Current menu source

The Cup Series and Bottle Series values were transcribed from the supplied menu images. Bottle prices are represented by 250 ml, 500 ml, and 1 liter variants.
