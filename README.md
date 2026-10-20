# Novel Nest — 10-page HTML/CSS Bookstore

Open `index.html` in your browser or use VS Code Live Server. No build steps or dependencies. Google Fonts are optional and require internet; fallback fonts work offline.

## Pages
1. index.html — Home
2. shop.html — All books
3. categories.html — Categories
4. new-arrivals.html — New arrivals
5. best-sellers.html — Best sellers
6. product.html — Sample product details
7. cart.html — Shopping cart placeholder
8. account.html — Sign-in UI
9. about.html — About
10. contact.html — Contact form
11. faq.html — FAQs (bonus)

## Future backend integration
Keep `book_id` stable (b001 etc). Move book records into a database and render cards from a server template or API-driven frontend. Suggested REST endpoints: GET /api/books, GET /api/books/:id, POST /api/auth/login, GET/POST /api/cart, POST /api/orders, POST /api/contact. Use server-side validation, password hashing, authorization, CSRF protection where applicable, and payment provider integrations. The current pages are static: product links open a sample product template; no real login, cart, search, checkout, email submission or payment is implemented. The footer signup form is a demo only.

## Urdu selection
Sample listings include Umera Ahmed, Nimra Ahmed, Farhat Ishtiaq, Bano Qudsia, Ashfaq Ahmed, Khadija Mastoor, Ghalib and Faiz. Urdu prices/stock are not verified. Covers are CSS placeholders.
