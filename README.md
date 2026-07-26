# Foxtons (foxtons)

Foxtons Group plc is a London-focused UK estate agency, founded in 1981 and listed on the London Stock Exchange, running residential sales, lettings and property management from roughly 40 branches across London and Surrey, plus independent mortgage broking through its Alexander Hall subsidiary. It sits on the brokerage rung of the value chain — it originates and holds the client and the listing rather than operating a portal or a data exchange — and distributes its stock to Rightmove and Zoopla through the UK's portal feed arrangements rather than through any shared cooperative, because the UK has no MLS. Its technology is deliberately proprietary: an internally built CRM/ERP called BOS underpins the whole business, and the My Foxtons customer portal is the consumer face of that same system. API posture, stated honestly, is none-published — no developer or partner portal, no api./developer./docs. host resolves, no OpenAPI or OData contract is served, and the only machine-readable public surface is schema.org JSON-LD embedded in its web pages. RESO is absent, as expected outside North America. The genuinely open UK property data layer belongs to government (HM Land Registry, Ordnance Survey), not to Foxtons.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/foxtons/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/foxtons/refs/heads/main/apis.yml)

## Tags

- Real Estate
- United Kingdom
- Property Listings
- Rentals
- Lettings
- Property Management
- Estate Agency
- Mortgage
- PropTech
- London

## Timestamps

- **Created:** 2026-07-26
- **Modified:** 2026-07-26

## APIs

No public APIs are documented by Foxtons. Every conventional developer entry point was probed on 2026-07-26 and none exists — `developer.`, `developers.`, `api.` and `docs.` subdomains of `foxtons.co.uk` all fail DNS resolution, and `/developers`, `/api`, `/docs`, `/api-docs`, `/openapi.json`, `/swagger.json` and `/$metadata` on `www.foxtons.co.uk` all return HTTP 404. No OpenAPI, OData `$metadata`, AsyncAPI, GraphQL, SDK, CLI, Postman collection, webhook catalogue or company GitHub organisation was found.

Search engines surface URLs on `https://api.foxtons.co.uk/` whose titles mirror ordinary marketing pages. **That host does not exist** — NXDOMAIN was confirmed at two independent public resolvers. Those results are search-index artifacts, not an API.

`robots.txt` disallows `/api/` and `/json/`, which tells us the website is backed by internal JSON endpoints. Those roots return 404, are undocumented and uncontracted, and are not a public API.

See [review.yml](review.yml) for the full probe log, RESO posture, access gate, open-data assessment and auth model.

## Sector Posture

| Fact | Finding |
| --- | --- |
| Home market | United Kingdom |
| Tier | Brokerage |
| RESO posture | No RESO reference found — RESO has no presence in the UK market, which has no MLS to certify |
| RESO certified | No |
| Access gate | `none-published` — nothing to sign, nothing to join, because nothing is offered |
| Open data | No — Foxtons publishes market reports as PDF only; the open UK property data layer is government-published (HM Land Registry, Ordnance Survey) |
| Auth model | None published; the only auth surface is the consumer My Foxtons sign-in, and no OpenID Connect discovery document is served |
| Machine-readable public surface | schema.org JSON-LD `Organization` markup only |

## Common Properties

- [Website](https://www.foxtons.co.uk/)
- [Website](https://www.foxtonsgroup.co.uk/)
- [About](https://www.foxtons.co.uk/foxtons/about)
- [Technology](https://www.foxtonsgroup.co.uk/about-us/our-technology)
- [Customer Portal](https://www.foxtons.co.uk/myfoxtons)
- [Reports](https://www.foxtons.co.uk/reports)
- [LinkedIn](https://www.linkedin.com/company/foxtons)
- [Twitter](https://x.com/foxtons)
- [Facebook](https://www.facebook.com/FoxtonsEstateAgent/)
- [Instagram](https://www.instagram.com/foxtonsestateagents/)

## Maintainers

- Kin Lane — kin@apievangelist.com
