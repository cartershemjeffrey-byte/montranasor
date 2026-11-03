# MONTRANASOR® website — first stage

This is a static storefront prototype built from the supplied page layouts. Open `index.html` in a browser or serve this folder locally.

## Included

- Responsive home, shop, collection, product, bag, checkout preview, and order confirmation pages.
- Account overview, order history, wishlist, addresses, account details, notifications, and order tracking screens.
- Size guide, FAQ, about, culture, contact, order policy, shipping, privacy, terms, and free pre-order information pages.
- Local browser demo interactions for cart, wishlist, and account screens.
- The bag limits each design to five pieces total across sizes in this browser demo. A server must enforce inventory limits for real orders.
- `admin.html` provides a local catalog editor for product photos, prices, sale prices, pre-order flags, and shop visibility. It is excluded from the public GitHub site.
- Generated monochrome angel and ruined-world backgrounds, plus the supplied wordmark crop, are separate assets with no text baked into the artwork.
- Cambodia shipping choices at $3 standard and $6 express. International quotes require a carrier integration.
- Free pre-orders require account verification, an availability notification, and a 72-hour payment deadline before automatic cancellation.

## Not connected yet

This static version has no server, protected admin authentication, email or SMS verification, inventory, scheduled cancellation job, real notification service, payment processor, carrier quote, or live order tracking. The admin editor saves only to this browser's local storage and is not private or shared across devices. Checkout is a non-payment demo. Do not collect customer data or present the prototype as a live store.

Before launch, add a secure server and database; protect the catalog editor with a server-side admin role for the store owner; store product photos in a managed object store; configure a legitimate payment provider and shipping carrier; configure email/SMS providers; implement verification, inventory locks, 72-hour expiry processing and audit logs; and review final consumer and privacy terms for Cambodia and intended destination countries. Keep all credentials in server environment variables.

The legal copy and mockup garment measurements are provisional. The display font approximates the supplied screenshots because the raster layouts do not include their original typeface file. Confirm production measurements and obtain applicable legal review before launch.
