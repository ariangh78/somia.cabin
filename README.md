# Somia bathroom storefront prototype

Persian RTL responsive website, tailored to the three supplied Somia catalogue posts: A724, A716, A719. Local screenshot assets are displayed through CSS crop windows to keep Instagram interface out of the layout. No image-generation or invented product photography is used.

## Run

Node 22.12+ or 24. `npm ci`, `npm run dev`. Production: `npm run build`, `npm run preview`.

## Features

Product filtering, product detail dialogs, persistent shortlist, removal, copyable price enquiry and link to Somia's Instagram. No payment processing, real order placement or automatic messages. Price and availability are deliberately omitted pending owner confirmation. All dimensions are copied from supplied catalogue screenshots and should be confirmed before purchase. Brand headlines are proposed copy, not verified company claims. Stock availability, materials, waterproofing, warranties and delivery are not asserted.

## Before presenting / launching

Obtain original high-resolution product assets and the exact brand logo. The current wordmark is a provisional text treatment. Confirm dimensions, included items, actual prices and policies with the owner. Optional typography loads from Google Fonts; Tahoma is the fallback. Product data is in main.js; styles are in style.css. Saved selections use localStorage key somia-selection-v2. This is a local prototype; deployment is separate.

## Category-page revision

The catalogue now opens with breadcrumbs, category navigation, a filter sidebar, model search, width sorting, empty-result recovery, and product cards. Mobile filters appear above the grid. Requested references: pakhshetehran.com and hogonik.com; both returned HTTP 403 from this environment, so this is an independently implemented category layout, not a verified visual reproduction of either site. REA repository inspected at 4eaf3a117b3f4863a994b9be743ec5bc1501e16c; published REA 6.7.0 CLI diagnostic and browser target discovery exercised. No REA code is embedded in the storefront. Supply screenshots or an authorized page export for a precise reference match.

Validation: production build, DOM interaction checks, and real Chromium checks for search, empty-result reset, sorting, saved selections, and mobile horizontal overflow at 390px.
