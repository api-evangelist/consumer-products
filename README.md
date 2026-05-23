# Consumer Products (consumer-products)

Industry-vertical index of APIs, data sources, syndication networks, and product information management (PIM) platforms that power the consumer packaged goods (CPG) and consumer products ecosystem. Catalogs corporate developer surfaces from large CPG manufacturers (P&G, Unilever, Nestle, Coca-Cola, PepsiCo, Mondelez, Kimberly-Clark, Colgate-Palmolive), product-identifier registries (GS1 Digital Link, GTIN/UPC lookup), open product databases (Open Food Facts, Open Beauty Facts), commercial syndication networks (Salsify, Syndigo, 1WorldSync), and PIM platforms (Akeneo, Pimcore, Plytix, Sales Layer).

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=topic-consumer-products&utm_content=repo)

## Tags

- Consumer Products, CPG, Product Data, Retail, GTIN, Barcode, Product Catalog, PIM, Syndication, Schema.org Product

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-23

## APIs

### GS1 Digital Link
GS1 Digital Link is the global standard that turns GS1 identifiers (GTINs, SSCCs, GLNs) into web URIs so a single barcode or QR code can connect to multiple sources of brand, regulatory, supply chain, and consumer information. It is the cornerstone identification standard for consumer products and underpins GS1 2D Sunrise 2027.

**Human URL:** [https://www.gs1.org/standards/gs1-digital-link](https://www.gs1.org/standards/gs1-digital-link)

#### Tags
 - GS1, Digital Link, GTIN, 2D Barcode, Identification

### Open Food Facts
Open Food Facts is a collaborative, free, open database of food products from around the world maintained by a global community of contributors. Its REST API exposes ingredients, nutrition facts, additives, allergens, Nutri-Score, NOVA group, packaging, and labels for over three million products keyed by barcode (GTIN/EAN/UPC).

**Human URL:** [https://world.openfoodfacts.org/](https://world.openfoodfacts.org/)

#### Tags
 - Open Data, Food, Nutrition, Ingredients, Barcode

### Open Beauty Facts
Open Beauty Facts is the Open Food Facts sister project covering cosmetics and personal care products. The same REST shape exposes ingredients (INCI), labels, packaging, and brand metadata for beauty products contributed by a global community and keyed by barcode.

**Human URL:** [https://world.openbeautyfacts.org/](https://world.openbeautyfacts.org/)

#### Tags
 - Open Data, Beauty, Cosmetics, INCI, Barcode

### Procter & Gamble (P&G) Brands
Procter & Gamble is the world's largest CPG company by revenue, operating ten product categories across Beauty, Grooming, Health Care, Fabric & Home Care, and Baby, Feminine & Family Care. P&G does not publish a public consumer-facing developer portal; integrations are restricted to retail trading partners, EDI/GS1 networks, and the P&G Direct direct-to-consumer commerce stack.

**Human URL:** [https://us.pg.com/brands/](https://us.pg.com/brands/)

#### Tags
 - CPG, Beauty, Grooming, Health Care, Home Care, Baby Care

### Unilever Brands
Unilever is a multinational CPG company with more than 400 brands across Beauty & Wellbeing, Personal Care, Home Care, Nutrition, and Ice Cream. Public APIs are not consolidated under a single developer portal; integrations run through retailer data syndication networks and brand-specific e-commerce platforms (e.g. Hellmann's, Dove, Magnum, Knorr).

**Human URL:** [https://www.unilever.com/brands/](https://www.unilever.com/brands/)

#### Tags
 - CPG, Beauty, Personal Care, Home Care, Food, Ice Cream

### Nestle Brands
Nestle is the world's largest food and beverage company with more than 2,000 brands across Beverages, Dairy, Confectionery, Nutrition, Pet Care, and Prepared Dishes. Like other large CPGs, Nestle has no public unified developer portal; product information flows through retailer syndication networks (1WorldSync, Salsify), GS1 GDSN, and brand-level commerce APIs such as Nestle Professional and Purina e-commerce.

**Human URL:** [https://www.nestle.com/brands](https://www.nestle.com/brands)

#### Tags
 - CPG, Food, Beverages, Dairy, Confectionery, Pet Care

### The Coca-Cola Company
The Coca-Cola Company manufactures more than 200 brands across sparkling soft drinks, water, sports drinks, juice, tea, coffee, and plant-based beverages. Public developer surfaces are limited to the Coca-Cola Freestyle dispenser ecosystem, the My Coke Rewards / Sip & Scan loyalty mechanics, and the Coca-Cola Vending API. Product master data is distributed via GS1 GDSN and Syndigo to North American retailers.

**Human URL:** [https://www.coca-colacompany.com/brands](https://www.coca-colacompany.com/brands)

#### Tags
 - CPG, Beverages, Soft Drinks, Loyalty, Vending

### PepsiCo Brands
PepsiCo operates a portfolio of 22 billion-dollar brands spanning Beverages (Pepsi, Gatorade, Tropicana, Lipton, Bubly) and Convenient Foods (Lay's, Doritos, Cheetos, Quaker, SodaStream). Developer integration occurs through PepsiCo Partners (retailer EDI), the Sodastream connected dispenser ecosystem, and PepsiCo Labs initiatives. There is no consolidated public API portal.

**Human URL:** [https://www.pepsico.com/brands](https://www.pepsico.com/brands)

#### Tags
 - CPG, Beverages, Snacks, SodaStream, Connected Devices

### Mondelez International
Mondelez International is the global snacks leader with billion-dollar brands including Oreo, Cadbury, Milka, Toblerone, Ritz, Trident, and Halls. Public-facing developer assets are limited; retail master data flows through 1WorldSync and GS1 GDSN, and direct-to-consumer brand experiences (e.g. SnackWorks recipe API for the US baking brands) are brand-specific rather than portfolio-wide.

**Human URL:** [https://www.mondelezinternational.com/snack-brands](https://www.mondelezinternational.com/snack-brands)

#### Tags
 - CPG, Snacks, Confectionery, Biscuits, Gum

### Kimberly-Clark Brands
Kimberly-Clark is a personal-care CPG making essentials in Family Care, Personal Care, and K-C Professional. Brands include Huggies, Kleenex, Scott, Cottonelle, Kotex, Depend, and Poise. Like its CPG peers, Kimberly-Clark does not publish a general developer portal; B2B and retail integrations rely on GS1 / GDSN data syndication and EDI.

**Human URL:** [https://www.kimberly-clark.com/en-us/brands](https://www.kimberly-clark.com/en-us/brands)

#### Tags
 - CPG, Personal Care, Family Care, Hygiene

### Colgate-Palmolive Brands
Colgate-Palmolive is a global CPG focused on Oral Care, Personal Care, Home Care, and Pet Nutrition (Hill's). Lead brands include Colgate, Tom's of Maine, Palmolive, Speed Stick, Softsoap, Ajax, Murphy Oil Soap, and Hill's Science Diet / Prescription Diet. Public API surfaces are limited to the Hill's Pet Nutrition product locator and brand commerce stacks; master data flows through GS1 GDSN to retailers.

**Human URL:** [https://www.colgatepalmolive.com/en-us/brands](https://www.colgatepalmolive.com/en-us/brands)

#### Tags
 - CPG, Oral Care, Personal Care, Home Care, Pet Nutrition

### Salsify Product Experience Cloud
Salsify is a Product Experience Management (PXM) platform that combines PIM, digital asset management, syndication, and digital shelf analytics. Salsify's REST APIs let brands centralize product content and syndicate it to thousands of retail destinations, marketplaces, and direct channels with channel-specific transformations and validation.

**Human URL:** [https://developers.salsify.com/](https://developers.salsify.com/)

#### Tags
 - PXM, PIM, Syndication, Digital Shelf, DAM

### Syndigo Content Experience Hub
Syndigo is a Master Data Management (MDM), PIM, and content syndication network that distributes product, location, and digital asset data to retailers and recipients across grocery, hardlines, foodservice, and healthcare. Syndigo APIs cover product content publishing, validation against retailer requirements, and digital asset delivery.

**Human URL:** [https://www.syndigo.com/](https://www.syndigo.com/)

#### Tags
 - MDM, PIM, Syndication, Content Experience, Retail

### 1WorldSync GDSN
1WorldSync is the largest GS1-certified Global Data Synchronization Network (GDSN) data pool, operating the Content1 platform for product content management and syndication. Brands publish master data once and synchronize it with subscribing retailers worldwide using GS1 standards (GTIN, GLN, GPC, GDSN messages).

**Human URL:** [https://www.1worldsync.com/](https://www.1worldsync.com/)

#### Tags
 - GDSN, GS1, Syndication, Master Data, Retail

### Akeneo Product Cloud
Akeneo is an open-source-rooted Product Information Management (PIM) platform. Its REST API exposes products, product models, families, attributes, categories, channels, locales, reference entities, and assets, enabling integration with e-commerce platforms, ERPs, syndication partners, and DAM systems.

**Human URL:** [https://api.akeneo.com/](https://api.akeneo.com/)

#### Tags
 - PIM, Open Source, Product Cloud, Catalog

### Pimcore Platform
Pimcore is an open-source Digital Experience Platform combining PIM, MDM, DAM, CDP, and DXP capabilities. Pimcore exposes both REST and GraphQL APIs (the Datahub) for product data, classification stores, object bricks, assets, documents, and customer data, with a strong focus on flexible data modeling.

**Human URL:** [https://pimcore.com/](https://pimcore.com/)

#### Tags
 - PIM, DAM, DXP, GraphQL, Open Source

### Plytix PIM
Plytix is a SaaS Product Information Management platform aimed at mid-market brands, with channel syndication, brand portals, and a public REST API for products, variants, attributes, categories, assets, and relationships, used to feed marketplaces (Amazon, Walmart) and e-commerce stacks.

**Human URL:** [https://help.plytix.com/en/api](https://help.plytix.com/en/api)

#### Tags
 - PIM, SaaS, Mid-Market, Syndication

### Sales Layer PIM
Sales Layer is a cloud PIM platform with REST API access to product catalogs, attribute schemas, categories, media, related products, and syndication channels. It connects brands and retailers across marketplaces, e-commerce platforms, and printed catalog workflows.

**Human URL:** [https://docs.saleslayer.com/](https://docs.saleslayer.com/)

#### Tags
 - PIM, SaaS, Cloud, Catalog

## Common Properties

- [Website](https://github.com/api-evangelist/consumer-products)
- [API Evangelist GitHub Organization](https://github.com/api-evangelist)
- [GS1 Standards (GTIN, GLN, GDSN, Digital Link, GPC)](https://www.gs1.org/standards)
- [schema.org/Product Vocabulary](https://schema.org/Product)
- [Open Food Facts Data Dumps](https://world.openfoodfacts.org/data)

## Features

| Name | Description |
|------|-------------|
| Global Product Identification | GS1-issued GTIN, UPC, EAN, and ISBN identifiers, increasingly carried in GS1 Digital Link URIs and 2D barcodes for omnichannel resolution. |
| Master Data Syndication | Centralized publishing of product master data through GDSN data pools (1WorldSync, Syndigo) so retailers receive consistent, validated attributes across regions. |
| Product Information Management | PIM platforms (Akeneo, Pimcore, Plytix, Sales Layer, Salsify) that model attribute families, variants, channels, locales, and assets for omnichannel commerce. |
| Nutrition And Ingredient Transparency | Open and commercial APIs surfacing ingredients, allergens, nutrition facts, Nutri-Score, NOVA classification, and additive data for food and beverage products. |
| Cosmetic And Personal Care Transparency | INCI ingredient lists, allergen flags, and packaging data for beauty and personal care products, exposed through Open Beauty Facts and retailer feeds. |
| Digital Shelf Analytics | Monitoring product content quality, search rank, ratings, reviews, pricing, and availability across retailer e-commerce sites and marketplaces. |

## Use Cases

| Name | Description |
|------|-------------|
| Product Onboarding To Retailers | Brands publish master data once into a GDSN data pool and syndicate to grocery, drug, mass, and club retailers with channel-specific validation. |
| Connected Packaging With 2D Barcodes | Replacing 1D UPC barcodes with GS1 Digital Link QR codes to expose brand experiences, regulatory data, supply chain provenance, and recycling guidance from a single scan. |
| Ingredient And Allergen Lookup | Consumer apps querying Open Food Facts or Open Beauty Facts by barcode to surface allergens, additives, certifications, and nutritional scoring. |
| PIM-Driven Marketplace Distribution | Mid-market brands using PIM platforms to push consistent catalogs to Amazon, Walmart, Target Plus, Shopify, and direct-to-consumer channels. |
| Regulatory Reporting And Recall Management | Tracing recalled lots, batch codes, and serialized units through GS1 identifiers and supply chain APIs to support food safety, FDA, USDA, and EU recall workflows. |

## Integrations

| Name | Description |
|------|-------------|
| GS1 Global Data Synchronization Network (GDSN) | The international network of certified data pools enabling brands and retailers to synchronize standardized product master data globally. |
| Schema.org Product | The web vocabulary used for embedding product, offer, and review markup in e-commerce pages and consumed by search engines and shopping platforms. |
| Amazon Selling Partner API | Marketplace API consumed by PIM platforms (Salsify, Plytix, Sales Layer) to push catalogs, manage listings, and read orders. |
| Shopify Admin API | DTC commerce API integrated by brands and PIM platforms for product, inventory, and order synchronization. |
| SAP S/4HANA And Oracle NetSuite | Enterprise resource planning systems where master product data originates and is published outward through PIM and syndication layers. |

## Artifacts

Machine-readable schemas, contexts, and example payloads describing the consumer products data model.

### JSON Schema

- [Consumer Product Schema](json-schema/consumer-product-schema.json)
- [Product Identifier Schema](json-schema/product-identifier-schema.json)
- [Nutrition Facts Schema](json-schema/nutrition-facts-schema.json)

### JSON Structure

- [Consumer Product Structure](json-structure/consumer-product-structure.json)
- [Product Identifier Structure](json-structure/product-identifier-structure.json)
- [Nutrition Facts Structure](json-structure/nutrition-facts-structure.json)

### JSON-LD

- [Consumer Products Context](json-ld/consumer-products-context.jsonld) — Linked-data context aligning the consumer product model to schema.org/Product, GS1 vocabulary, and Open Food Facts terms

### Examples

- [Consumer Product (Food) Example](examples/consumer-product-food-example.json) — Lay's Classic Potato Chips, 225 g
- [Consumer Product (Beauty) Example](examples/consumer-product-beauty-example.json) — Dove Beauty Bar, White, 4 Bar Pack
- [Consumer Product (Household) Example](examples/consumer-product-household-example.json) — Tide Pods Original Laundry Detergent, 42 Count

## Vocabulary

- [Consumer Products Vocabulary](vocabulary/consumer-products-vocabulary.yml) — Unified taxonomy mapping 10 APIs, 9 resources, 9 actions, 5 workflows, 8 personas, and 4 domains across the consumer products landscape

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
