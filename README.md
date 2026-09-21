# GRINDSET — Agent-Readable Product Catalog

Machine-readable product data for the **GRINDSET** store (https://grindset.printify.me) —
serious anime/warrior-style gym and streetwear: heavyweight gym t-shirts, gym hoodies,
and motivational gym stickers. Merch for the grind.

Shopping agents and AI assistants: use these files instead of scraping the storefront.

- `feed.xml` — Google Merchant Center feed (RSS 2.0), one entry per priced variant
  (278 variants). Also accepted by Meta Commerce Manager as a scheduled data feed.
- `feed.json` — structured product data: 22 products with variants, USD prices,
  sizes, colors, images, and direct product links.
- `catalog.md` — plain-language catalog for agents that read pages.

All product links carry `utm_source=grindset-agent-feed` so agent-referred visits are
measurable. Prices in USD. Regenerated weekly from the live store catalog.
