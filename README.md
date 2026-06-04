# Harvard University (harvard)

Harvard University (QS World 2025 #4) maintains a substantial public developer footprint across several units. Its most prominent fully public APIs are the Harvard Art Museums API and the Harvard Library LibraryCloud / Open Metadata API. HUIT operates a central API Portal (HarvardKey-gated) for administrative APIs, and the DASH repository exposes an open OAI-PMH feed.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/harvard/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=harvard-api-evangelist&utm_content=repo)

## Type
- **x-type:** Index (Consumer / 3rd-Party)

## Tags
- Education, Higher Education, University, Research, Libraries, Museums, Open Metadata, OAI-PMH

## APIs
- **Harvard Art Museums API** — REST/JSON collections data (21 resources) with IIIF. Base `https://api.harvardartmuseums.org`. Free, non-commercial, API key required. [Docs](https://github.com/harvardartmuseums/api-docs)
- **LibraryCloud API (Open Metadata)** — 12.7M+ bib records as MODS/Dublin Core; public Item API needs no key. Base `https://api.lib.harvard.edu/v2/items.json`. [Docs](https://library.harvard.edu/services-tools/harvard-library-apis-datasets)
- **DASH OAI-PMH** — Open-access repository (58,000+ works) metadata harvesting. Base `https://dash.harvard.edu/server/oai/request`.
- **Harvard API Portal (HUIT)** — Courses, Person, Dining, Zoom, Library Catalog, GenAI; HarvardKey-gated. [Catalog](https://portal.apis.huit.harvard.edu/apis)

## Plans, Rate Limits, FinOps
- [Plans](plans/harvard-plans-pricing.yml) — Free/open public APIs; HarvardKey-gated administrative APIs.
- [RateLimits](rate-limits/harvard-rate-limits.yml) — Art Museums ~2,500 calls/day; harvest open feeds politely.
- [FinOps](finops/harvard-finops.yml) — Non-commercial; no usage-based API billing.

## Timestamps
- **Created:** 2026-06-03
- **Modified:** 2026-06-03

## Common Properties
- [Website](https://www.harvard.edu/)
- [Developer / Data](https://data.harvard.edu/developers)
- [GitHub](https://github.com/harvard)
- [Status](https://status.huit.harvard.edu/)

## Notes
- Two genuinely open public APIs verified live: Harvard Art Museums (free key) and LibraryCloud Item API (no key, returned live MODS JSON). DASH OAI-PMH returned valid OAI-PMH XML. See [review.yml](review.yml).
- HUIT API Portal base URLs are gated behind HarvardKey + app registration; only the human-readable OpenAPI doc pages are public.
- The correct library GitHub org is `harvard-library` (`harvardlibrary` does not exist).

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
