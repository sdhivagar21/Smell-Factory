# Smell Factory

The Smell Factory perfume store website, in the Arzi Perfumes design with Adil Qadri–style offers.

## View it

Double-click `index.html`. The whole website is inside that one file, so it opens straight in your browser.

## Put it online with GitHub Pages

1. On GitHub, open this repository and go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**, then choose branch **main** and folder **/ (root)**. Click **Save**.
3. After a minute or two the site is live at **https://sdhivagar21.github.io/Smell-Factory/**

## What's inside

- **Home page:** offer banner, Build Your Bundle, Best Sellers, Collections (Best Sellers, Recreations, SF Blends, Gift Sets), a second offer banner, Shop by Occasion, reels, Why Trust Us.
- **Offers:** Buy 2 Get 1 Free on 50 ml and 100 ml perfumes, and any 4 × 20 ml for ₹1,199. Both are on the **Build Your Bundle** page, and the bag shows the free bottle.
- **On phones:** a tab bar with Home, Best Sellers, Buy 2 Get 1, Recreations and Cart.
- **Product page:** 1 / 2 / 3 bottle choices that show the free bottle, Add to cart and Buy it now.
- Product photos load from Cloudinary.

## On its own vs. with the store server

This page is built from the full store project (Node.js server, admin panel, database and Razorpay checkout). Hosted here on its own, with no server:

- it shows the catalogue built into the page (13 perfumes and their prices);
- orders are sent on WhatsApp (+91 86818 05523), since online payment needs the server;
- changes made in the admin panel don't appear here.

## Updating

Replace `index.html` with a new build (`storefront/dist/index.html` from the store project, after `npm run build`), then commit and push.
