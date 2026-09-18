GSM MARKET

GSM Market is a concept storefront website for a small South African retail
shop selling mobile phones, accessories, electronics, clothing and everyday
essentials. It's built as a plain HTML and CSS site — there is no
JavaScript, no build step and no backend anywhere in the project.

PAGES
- index.html: the homepage, with a hero banner, a department overview,
  a shortlist of featured products and a few items under R500.
- products.html: every product in the catalogue, grouped by category.
- mobile-phones.html, accessories.html, electronics.html, clothing.html,
  everyday-items.html: one page per department.
- about.html: a short introduction to the shop.
- contact.html: contact details and an enquiry form.

THE CATALOGUE
Twenty products are shown across the five departments — real, named items
(Samsung, Lenovo, Anker, Levi's and others) rather than filler placeholders.
Each product card shows its own photo, name, description and a guide price
in South African Rand. The photos are real product photos sourced from
retailer listings; a few are labelled "Example photo" where the exact model
shown isn't confirmed. See assets/products/README.md and sources.json for
where each photo came from.

GETTING IN TOUCH
There's no shopping cart, search or checkout — this is a browsing catalogue,
not a working online store. Instead, every product links to the contact
page, and the enquiry form there opens the visitor's email app addressed to
the shop (support@gsmmarket.co.za), alongside a phone number
(+27 78 306 1787) for people who'd rather call.

DESIGN
The look is a navy-and-lime storefront style, laid out in styles.css, and
responsive from desktop down to phone-sized screens.
