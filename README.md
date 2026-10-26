# Foxtons (foxtons)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
