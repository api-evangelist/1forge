# 1Forge (1forge)

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

1Forge delivers real-time forex and cryptocurrency quotes for 700+ currency pairs through a simple JSON REST API and a low-latency WebSocket stream. The product targets trading apps, multi-currency checkout flows, treasury and FinOps tooling, and any workload that needs FIX-speed price data without the FIX-grade integration cost.

**APIs.json:** [https://1forge.com/forex-data-api/api-documentation](https://1forge.com/forex-data-api/api-documentation)

## Tags

- Currency Exchange
- Forex
- Cryptocurrency
- Market Data
- Financial Data
- Real-Time Data

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-28

## APIs

### 1Forge Forex Data API

Real-time bid/ask quote retrieval, currency conversion, symbol discovery, market status, and quota inspection for 700+ forex and cryptocurrency pairs served from four global edges (Oregon, Virginia, Taiwan, Belgium).

- **Human URL:** [https://1forge.com/forex-data-api/api-documentation](https://1forge.com/forex-data-api/api-documentation)
- **Base URL:** `https://api.1forge.com`

#### Tags

- Currency Exchange
- Forex
- Cryptocurrency
- Market Data
- REST

#### Properties

- [Documentation](https://1forge.com/forex-data-api/api-documentation)
- [OpenAPI](openapi/1forge-forex-data-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/1forge-forex-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/1forge-forex-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://github.com/1Forge/javascript-forex-quotes)
- [SDK](https://github.com/1Forge/php-forex-quotes)
- [SDK](https://github.com/1Forge/python-forex-quotes)
- [SDK](https://github.com/1Forge/java-forex-quotes)
- [SDK](https://github.com/1Forge/golang-forex-quotes)
- [SDK](https://github.com/1Forge/dotnet-forex-quotes)

### 1Forge Forex Stream

WebSocket stream that delivers real-time bid/ask updates for subscribed forex and cryptocurrency pairs. Streaming is gated to paid plans.

- **Human URL:** [https://1forge.com/forex-data-api/api-documentation](https://1forge.com/forex-data-api/api-documentation)
- **Base URL:** `wss://sockets.1forge.com/socket`

#### Tags

- Currency Exchange
- Forex
- Cryptocurrency
- Market Data
- WebSocket
- Streaming

#### Properties

- [Documentation](https://1forge.com/forex-data-api/api-documentation)
- [AsyncAPI](asyncapi/1forge-forex-stream-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [SDK](https://github.com/1Forge/javascript-forex-quotes)
- [SDK](https://github.com/1Forge/php-forex-quotes)
- [Postman Collection](collections/1forge-forex-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/1forge-forex-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://1forge.com)
- [Documentation](https://1forge.com/forex-data-api/api-documentation)
- [Sign Up](https://1forge.com/register)
- [Pricing](https://1forge.com/pricing)
- [Terms of Service](https://1forge.com/terms)
- [GitHub Organization](https://github.com/1Forge)
- [Plans](plans/1forge-plans-pricing.yml)
- [Rate Limits](rate-limits/1forge-rate-limits.yml)
- [Fin Ops](finops/1forge-finops.yml)
- [Vocabulary](vocabulary/1forge-vocabulary.yml)
- [Spectral Rules](rules/1forge-rules.yml)
- [JSON-LD](json-ld/1forge-forex-data-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Public APIs Listing](https://github.com/public-apis/public-apis)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
