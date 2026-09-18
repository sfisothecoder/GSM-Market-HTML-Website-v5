GSM MARKET STOREFRONT

PREVIEW
Open index.html directly in a browser, or use a local static server:
  python3 -m http.server 8000
Then visit http://localhost:8000.
This is a plain HTML and CSS website — no JavaScript, no build tools and no
third-party script dependencies are used anywhere on the site.

FILES
- styles.css: responsive navy-and-lime storefront design.
- index.html, products.html, mobile-phones.html, accessories.html,
  electronics.html, clothing.html, everyday-items.html, about.html,
  contact.html: static pages. Every product card is hand-written HTML;
  there is no catalogue data file or client-side rendering.
- assets/products/: locally stored product photos and source manifest.
  Example photos are labelled for catalogue entries without exact model/style data.
  Google Fonts and the shop lifestyle photo use external services.

SHOPPING
There is no shopping bag, search, filtering or sorting — all of that required
JavaScript and has been removed. Each product card links to the contact page
so a visitor can ask about that item directly. The contact form submits via
a mailto: action (support@gsmmarket.co.za), which opens the visitor's own
email app with the message pre-filled — it does not send anything on its
own, and relies on the visitor's device having an email app configured.
Phone (+27 78 306 1787) and email (support@gsmmarket.co.za) are listed on
the contact page; confirm these are correct before relying on them.

BEFORE SELLING
Confirm the catalogue specifications, product imagery, selling prices and stock.
Provide business contact details, delivery, returns and warranty terms.
Connect an order service and payment provider to accept real purchases.
Never collect card details in the static website.
