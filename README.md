# PT. Bumi Ruma Nusantara - Official Website (rumavanilla.com)

Official B2B multi-page export website for **PT. Bumi Ruma Nusantara** ([rumavanilla.com](https://rumavanilla.com)), premier Indonesian agricultural exporter specializing in high-vanillin Planifolia and Tahitian vanilla beans.

---

## 🌿 Overview

This repository contains the production-ready source code for the official corporate export portal:
- **Domain**: [rumavanilla.com](https://rumavanilla.com)
- **Email**: hello@rumaexport.com
- **WhatsApp**: +62 851-1741-0114
- **Instagram**: [@ruma.vanilla](https://www.instagram.com/ruma.vanilla/)
- **Corporate Office & Curing Facility**: Babakan, Kec. Cisaat, Kab. Sukabumi, Jawa Barat 43152, Indonesia

---

## 📑 Pages & Architecture

### 1. Core Website Pages (Root)
- **`index.html`** (Home) - Strategic sourcing advantages, commercial grades overview, laboratory certification metrics, and inquiry forms.
- **`about.html`** (About Us) - Company heritage, Sukabumi volcanic terroir, sustainable agroforestry philosophy, and team profiles.
- **`products.html`** (Products) - Comprehensive export product directory with specifications, moisture thresholds, and packaging details.
- **`sustainability.html`** (Sustainability) - Regenerative agroforestry practices, direct-trade farmer equity, and EUDR compliance.
- **`contact.html`** (Contact & Export Inquiry) - Direct procurement channel with quotation forms, Incoterms options, and global shipping ports.

### 2. Product Technical Dossiers (`/product/`)
- **`product/index.html`** - Centralized commodity index and technical catalog.
- **`product/vanilla-planifolia-gourmet.html`** - Vanilla Planifolia Gourmet Grade A (14–19cm, 28–35% moisture, vanillin >2.0%).
- **`product/tahitian-vanilla.html`** - Indonesian Tahitian Vanilla Grade A (16–17cm, floral/fruity profile, anisyl compounds).
- **`product/pure-vanilla-powder.html`** - 100% Pure Vanilla Powder (clean-label, 50–150µm mesh, zero carriers).

### 3. B2B Sourcing Hub & Keyword Portals (`/supplier/`)
- **`supplier/index.html`** - Master directory showcasing all 25 transactional portals categorized by buyer intent.
- **25 Parent Keyword Landing Pages**:
  1. `supplier/indonesian-vanilla-beans-supplier.html` (Master Pillar)
  2. `supplier/vanilla-beans-wholesale.html`
  3. `supplier/bulk-vanilla-beans-supplier.html`
  4. `supplier/vanilla-beans-exporter.html`
  5. `supplier/buy-vanilla-beans-in-bulk.html`
  6. `supplier/wholesale-vanilla-pods.html`
  7. `supplier/vanilla-beans-manufacturer-direct.html`
  8. `supplier/b2b-vanilla-supplier.html`
  9. `supplier/grade-b-vanilla-beans-wholesale.html`
  10. `supplier/extraction-grade-vanilla-beans.html`
  11. `supplier/gourmet-grade-vanilla-beans-wholesale.html`
  12. `supplier/high-vanillin-content-vanilla-beans.html`
  13. `supplier/vanilla-planifolia-beans-bulk.html`
  14. `supplier/tahitian-vanilla-beans-wholesale.html`
  15. `supplier/vanilla-tahitensis-bulk-supplier.html`
  16. `supplier/sun-cured-vanilla-beans-bulk.html`
  17. `supplier/organic-vanilla-beans-wholesale.html`
  18. `supplier/sustainably-sourced-vanilla-beans.html`
  19. `supplier/fair-trade-vanilla-beans-exporter.html`
  20. `supplier/java-vanilla-beans-wholesale.html`
  21. `supplier/direct-supplier-vanilla-indonesia.html`
  22. `supplier/sumatra-planifolia-vanilla-beans.html`
  23. `supplier/papua-tahitian-vanilla-beans-bulk.html`
  24. `supplier/vanilla-beans-supplier-usa.html`
  25. `supplier/vanilla-beans-supplier-europe.html`

### 4. International Geotargeting Destination Network (`/supplier/{keyword}/{country}.html`)
- **Subfolder Architecture**: Structured as `/supplier/[keyword]/[country-slug].html`.
- **4,900 Country Destination Landing Pages**: Generated across all 25 keywords for 196 sovereign nations worldwide (e.g. `supplier/vanilla-beans-wholesale/united-states.html`, `supplier/bulk-vanilla-beans-supplier/germany.html`, etc.).
- **Localized Technical Optimization**:
  - Exact `<link rel="canonical">` per country URL.
  - Schema.org `WholesaleStore` with localized `"areaServed": {"@type": "Country", "name": "...", "identifier": "..."}`.
  - 4-Tier Schema.org `BreadcrumbList` (`Home > Supplier Hub > Keyword > Country`).
  - Country-specific Title, Meta Description, OpenGraph, and Twitter tags.
  - Hero H1 and Subtitle customized with destination country and door-to-port Incoterms (CIF / FOB).
  - Preserves 17 content sections, 11 detailed FAQs, and 100% identical navigation header, footer, and floating WhatsApp contact button (`+62 851-1741-0114`).
