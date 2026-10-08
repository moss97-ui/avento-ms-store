# Avento MS practice storefront

A static practice storefront for ESG, ISO 27001:2022 ISMS, and ISO 9001:2015 QMS Notion templates.

## Run

Open `dist/index.html` in your browser. No installation or build step is required.

## Features

Product filtering, detailed product dialogs, an in-memory cart, removal, demo order review, simulated completion, and a sample text-guide download. Cart contents reset on reload. Checkout collects no personal or payment information. There is no actual template delivery, payment, email, backend, or database.

Prices (USD 79, 99, 89) are illustrative. Product copy is adapted from the owner's supplied descriptions and a bounded review of the Notion system navigation. Preview layouts and records are illustrative, not screenshots. Private Notion pages, full template content, customer data, and duplication links are not included.

## Deploy the practice site

Use a public GitHub repository, then Settings → Pages → Source → GitHub Actions. The workflow checks JavaScript syntax and required files, packages `dist`, and publishes after a successful push to `main`. It does not check all behavior or replace a manual review.

## Edit

- Product descriptions, illustrative prices, cart and demo checkout: `dist/app.js`.
- Page structure: `dist/index.html`.
- Visual styling: `dist/style.css`.
- Deployment automation: `.github/workflows/pages.yml`.

Use branches and pull requests before merging changes into `main`.

## Before real sales

GitHub Pages is for this non-transactional practice demonstration. Move the real storefront to suitable hosting before connecting commerce, as GitHub Pages is not intended for websites primarily facilitating commercial transactions. Choose a checkout and digital delivery provider, confirm real product editions/content/licensing/prices, add accurate customer-facing terms and privacy information, and test purchase and delivery in the provider's sandbox. Keep actual paid template links and credentials out of public source code. Static browser code cannot protect a download link.

The supplied quality product description uses ISO 9001:2015, while a fetched private manual referred to a different edition. The practice store follows the supplied product description; reconcile the actual delivered template before real sales.

WebMCP is feature-detected for adding a product to the demo cart. Unsupported browsers simply use the visible controls. No payment or order completion tool is exposed.
