# Garden City Computers — Store + CRM

Functional prototype built as a self-contained responsive web app.

## Included
- Storefront, category browsing, search, cart and checkout/order creation
- Custom PC / quote request
- Repair/service ticket creation
- CRM dashboard with Leads, Customers, Orders, Products, Inventory, Service Tickets and Analytics
- Payment Gateway settings UI with Razorpay, Stripe, Cashfree and PayU options
- LocalStorage persistence for prototype data
- Responsive mobile/tablet/desktop UI

## Production payment note
The gateway screen is intentionally a configuration UI. Real payments require merchant credentials, server-side signature/webhook verification, HTTPS, and secure secret storage. Do not put secret keys in browser code.

## Run
Open `index.html` in a modern browser.
