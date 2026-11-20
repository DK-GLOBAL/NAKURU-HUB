# NakuruHub — portable starter project

This ZIP contains a self-contained, responsive marketplace frontend based on the NakuruHub source snapshot and product structure.

## Run it
- Unzip the folder.
- Open `index.html` in a modern browser, or upload the folder to any static host (Netlify, Cloudflare Pages, GitHub Pages, cPanel, etc.).
- No build step is required.

## Included
- Responsive landing page and navigation
- Category discovery: Property, Vehicles, Shopping, Services, Jobs, Events, Stays and Food
- Search, category filters and sorting
- Listing detail view
- Save/favourites using browser localStorage
- Add-listing form with client-side validation
- Sample marketplace data

## Important limitations
This is a portable frontend starter, not a production-connected copy of the hosted NakuruHub backend. The original AppDeploy source snapshot includes an authenticated listing API and database-backed listing persistence. This ZIP does not contain the live database, account credentials, provider secrets, or production environment configuration. New listings and saved items in this portable build are stored only in the current browser.

Before accepting real users or payments, connect authentication, persistent database storage, image uploads, seller contact/messaging, moderation, and payment processing. Do not treat the sample listings or demo interactions as verified transactions.

## Project files
- `index.html` — page structure
- `styles.css` — responsive visual system
- `app.js` — marketplace interactions and demo data
- `README.md` — setup and integration notes
