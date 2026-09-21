# GRINDSET agent catalog

Machine-readable product data for the GRINDSET store (https://grindset.printify.me),
so shopping agents can find and buy GRINDSET products.

- `feed.xml` — Google Merchant Center feed (RSS 2.0), one entry per priced variant.
- `feed.json` — structured product data: products, variants, prices, links, images.
- `catalog.md` — plain-language catalog for agents that read pages.

All product links carry `utm_source=grindset-agent-feed` so agent-referred visits
are measurable. Prices in USD. Regenerated from the live store catalog.
