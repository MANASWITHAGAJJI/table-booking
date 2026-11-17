# TableBook — Restaurant Table Booking System

A responsive, frontend-only restaurant reservation management dashboard built with HTML5, CSS3 and vanilla JavaScript.

## Run locally
1. Download and extract the project ZIP.
2. Open `index.html` in a modern browser.
3. No server, database, package installation or build step is required.

## Features
- Dashboard with booking totals, today's reservations, table availability, occupancy and estimated revenue.
- Table management: add, edit, delete, search and filter tables.
- Booking management: create, edit, delete, search and filter reservations.
- Customer management: add, edit, delete, search and view customer information.
- Visual floor layout with table statuses.
- Availability checker by date, time and party size, including overlapping booking checks.
- Monthly booking calendar with day details.
- CSV booking report export.
- Simulated confirmation and sign-out actions.
- Responsive sidebar and mobile layout.
- Dark mode.
- Data persists in browser `localStorage`.

## Demo data and limitations
The app starts with sample restaurant tables, customers and bookings. All data is stored locally in the browser. Clearing browser storage resets the demo data. There is no real authentication, server, database, email delivery, payment processing or PDF export. The confirmation message is simulated.

Revenue in the dashboard is a sample estimate of ₹500 per guest for confirmed and seated bookings; it is not actual payment data.

## Project files
- `index.html` — page structure
- `style.css` — design and responsive styles
- `script.js` — app data, rendering and interactions

## Suggested GitHub Pages deployment
1. Create a public GitHub repository.
2. Upload `index.html`, `style.css`, `script.js` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the deployment URL shown in the Pages settings.
