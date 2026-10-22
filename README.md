# DriveMarket — Automotive E-commerce Frontend Template

A responsive four-page automotive marketplace prototype built with HTML, CSS, JavaScript, Bootstrap 5, and Bootstrap Icons.

## Pages
1. `index.html` — homepage, three-slide hero, quick search, featured vehicles and categories.
2. `cars.html` — vehicle inventory with search, filters and sorting.
3. `vehicle.html` — vehicle detail page selected using `?id=1`, image gallery, specifications, add-to-cart and accessories.
4. `contact.html` — about information and enquiry form.

Cart, checkout and demo order confirmation are integrated as an offcanvas panel and modal workflows, not separate main pages.

## Run it
Open `index.html` in a browser, or serve the folder with a local development server. Bootstrap is loaded from a CDN, so an internet connection is required for Bootstrap and remote sample images.

## Current frontend demo functionality
- Responsive navigation/footer shared across all four pages.
- Three automatically rotating homepage hero slides.
- Search by keyword/body type/budget.
- Listing filters and sort controls.
- Vehicle detail pages using URL parameters.
- Cart add/remove/quantity controls stored in browser `localStorage`.
- Checkout form validation and browser-only demo confirmation.
- Contact form validation and demo feedback.

## Important before production
This is a **frontend template only**, not a production e-commerce system. Vehicle records, prices, product data and image URLs are sample/demo content. The checkout does not take payments, create server-side orders, reserve stock, send email/SMS, or authenticate administrators. Do not accept real orders or payments using this template alone.

To meet the full finalized scope, next add a backend API and database, administrator authentication/roles, vehicle/product/image management, inventory transactions, server-side price and stock validation, order management, notification service, and a payment gateway supported by the business's country/currency/account. Verify payments through authenticated provider webhooks; never store raw card details. Vehicle purchases may require quotation/deposit/import/shipping rules rather than a simple product checkout.
