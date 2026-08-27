# Awesome-Retail-Point-Of-Sale

## Top Retail Point of Sale (POS) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on In-Store Checkout, Inventory, Payments, Omnichannel Retail & Store Operations*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Retail Point of Sale (POS)**. These systems process in-store transactions, manage inventory and staff, accept payments, and increasingly connect physical stores with ecommerce and other channels.

**Examples** include Shopify POS, Square POS, Lightspeed Retail (including Vend), Clover, Revel Systems, Heartland Retail, KORONA POS, ERPLY, and EPOS Now (the category leaders).

**Open-source emphasis**: Retail POS has strong open-source options. **Odoo POS**, **ERPNext** (and community POS apps such as KLiK PoS / antPOS), **MyCompany**, and related projects provide full self-hosted checkout and inventory stacks. This section is expanded with these tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Shopify POS](https://www.shopify.com/pos)**  
  Omnichannel POS tightly integrated with the Shopify ecommerce platform — ideal for brands that sell both online and in physical stores.

- **[Square POS / Square for Retail](https://squareup.com/us/en/point-of-sale)**  
  Accessible, hardware-flexible POS popular with small and growing retailers; strong free tier and straightforward payment processing.

- **[Lightspeed Retail](https://www.lightspeedhq.com/retail/)**  
  Feature-rich retail POS (including the former Vend product) known for advanced inventory, multi-location support, and specialty retail workflows.

- **[Clover](https://www.clover.com/)**  
  Widely deployed POS with flexible hardware and an app market, often sold via payment resellers with bundled processing.

- **[Revel Systems](https://revelsystems.com/)**  
  iPad-based POS platform used in retail and hospitality for high-volume, configurable store operations.

- **[Heartland Retail](https://www.heartlandpaymentsystems.com/)**  
  Retail POS and payments solutions aimed at mid-market and specialty merchants.

- **[KORONA POS](https://koronapos.com/)**  
  Cloud POS focused on retail and high-risk or specialized merchants, with real-time inventory and offline capability.

- **[ERPLY](https://erply.com/)**  
  Cloud retail POS and inventory platform used by multi-store retailers needing centralized stock and sales visibility.

- **[EPOS Now](https://www.eposnow.com/)**  
  Cloud POS and business management system popular with small and mid-sized retailers, especially in the UK and related markets.

## Open-Source GitHub Projects
- **[Odoo Point of Sale](https://www.odoo.com/app/point-of-sale-shop)**  
  Full-featured open-source (and enterprise) POS module within the Odoo ERP suite — barcode, offline mode, multi-store, and deep integration with inventory and accounting.

- **[ERPNext](https://github.com/frappe/erpnext)**  
  Free and open-source ERP with built-in Point of Sale capabilities for retail and distribution, including stock, pricing, and sales invoices.

- **[KLiK PoS](https://github.com/Beveren-Software-Inc/KLiK_PoS)**  
  Modern, open-source Point of Sale built for ERPNext — responsive UI and feature set designed for retail businesses.

- **[antPOS](https://github.com/anthertech/antPOS)**  
  Open-source POS for ERPNext/Frappe using Vue.js, creating standard sales invoices and integrating tightly with Frappe APIs.

- **[MyCompany](https://github.com/lsfusion-solutions/mycompany)**  
  Free, open-source, self-hosted ERP/CRM for small businesses that includes a retail POS module alongside inventory, invoicing, and more.

- **[URY](https://github.com/ury-erp/ury)**  
  Open-source restaurant-focused management system on ERPNext (POS, kitchen display, etc.) — useful reference for hospitality-adjacent retail use cases.

- **[Chromis POS / similar legacy open POS](https://github.com/)**  
  Community-maintained open POS systems historically popular for independent retailers (availability and activity vary).

- **[Apache OFBiz](https://ofbiz.apache.org/)**  
  Open-source enterprise automation suite that includes point-of-sale and retail components for organizations willing to invest in configuration.

- **[Self-hosted payment terminal and receipt open stacks](https://github.com/)**  
  Libraries and examples for receipt printing, cash drawer control, and basic payment device integration with open POS backends.

- **[Inventory and barcode open tools paired with POS](https://github.com/)**  
  Open inventory and labeling projects that feed or complement self-hosted POS systems.

### Additional Strong Open-Source Options
- Running Odoo or ERPNext POS on a local server or VPS with Stripe/PayPal or local payment gateways.
- Combining open POS with open ecommerce (Saleor, Medusa, etc.) for true omnichannel ownership.
- Using offline-first progressive web apps on tablets as the cashier interface.
- Open reporting (Metabase, Superset) on top of POS sales and inventory data.
- Community localization and fiscalization modules for tax and receipt compliance in specific countries.

**Frameworks for building custom systems**: Deploy **Odoo POS** or **ERPNext** (with KLiK PoS / antPOS) for a complete self-hosted retail stack — products, inventory, checkout, and accounting in one database. Add payment gateway integrations and receipt hardware as needed. This eliminates monthly POS SaaS fees and keeps data on your infrastructure. Commercial platforms still lead in polished hardware ecosystems, consumer payment experience, large app marketplaces, and turnkey omnichannel (especially Shopify POS for Shopify brands and Square for rapid small-business setup).

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- POS systems handle payments and often personal data. Open-source deployments must address PCI scope (or use hosted payment fields), secure device management, backups, and local fiscal/tax requirements. Hardware compatibility and offline reliability should be thoroughly tested before live use.
- Payment processing rates and contracts vary widely; evaluate total cost of ownership, not only software license fees.

---
**Made for retailers, multi-store operators, and commerce technologists who want ownership of their checkout stack.**
Let's make in-store technology more open, affordable, and under merchant control.
