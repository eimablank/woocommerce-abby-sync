# WooCommerce Abby Sync

Lightweight WooCommerce integration for Abby accounting software.

Automatically synchronize WooCommerce orders with Abby draft invoices while preserving WooCommerce as the main commercial source of truth.

---

## Features

- Automatic Abby draft invoice creation
- WooCommerce customer synchronization
- French VAT support
- Multiple VAT rates support
- Product line synchronization
- SKU synchronization
- Shipping cost synchronization
- Duplicate prevention
- Lightweight architecture
- No Zapier or Make dependency

---

## Designed for

- Artists
- Designers
- Freelancers
- French businesses
- WooCommerce stores
- Abby accounting users

---

## Workflow

```text
WooCommerce
→ WooCommerce VAT
→ Order
→ WooCommerce Abby Sync
→ Abby Draft Invoice
```

WooCommerce remains the primary source for:

- products
- taxes
- pricing
- checkout
- customer management

Abby handles:

- invoicing
- accounting
- French compliance

---

## Supported VAT Rates

Examples:

| VAT Type | Rate |
|---|---|
| Standard | 20% |
| Reduced Art VAT | 5.5% |
| Author Rights | 10% |
| Export | 0% |

VAT is calculated directly from WooCommerce orders.

---

## Requirements

- WordPress
- WooCommerce
- Abby account
- Abby API key

---

## Installation

1. Upload plugin ZIP
2. Activate plugin
3. Enter Abby API key
4. Configure WooCommerce taxes
5. Start synchronizing orders

---

## Synchronization

The plugin automatically:

- creates Abby contacts
- creates Abby draft invoices
- sends product lines
- sends VAT rates
- sends payment method
- prevents duplicates

---

## Philosophy

This plugin intentionally stays lightweight.

WooCommerce handles commerce.  
Abby handles accounting.

The plugin acts only as a synchronization bridge.

---

## Roadmap

Planned features:

- Admin settings page
- Invoice resend button
- Logs viewer
- Abby marketplace integration
- French e-invoicing compatibility

---

## License

Copyright © Sandrine GERMAIN

All rights reserved.

---

## Commercial Version & Support

Official stable releases, support and installation services are available on:

https://sandrinegermain.com

---

## Support

https://sandrinegermain.com
