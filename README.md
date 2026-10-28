# 1Forge

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

**Areas:** Foreign Exchange · Cryptocurrency · Market Data · Financial Data · Real-Time Data · Real-Time

## 1Forge on APIs.io

Everything profiled for 1Forge is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/1forge/](https://apis.io/providers/1forge/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [1Forge Forex Stream](https://apis.io/apis/1forge/1forge-forex-stream/) — WebSocket stream that delivers real-time bid/ask updates for subscribed forex and cryptocurrency pairs. Streaming is gated to paid plans.
- [1Forge Convert API](https://apis.io/apis/1forge/1forge-convert-api/) — Convert a quantity from one currency into another at the current rate.
- [1Forge Market Status API](https://apis.io/apis/1forge/1forge-market-status-api/) — Check whether the forex market is currently open.
- [1Forge Quota API](https://apis.io/apis/1forge/1forge-quota-api/) — Inspect API key consumption and remaining quota.
- [1Forge Quotes API](https://apis.io/apis/1forge/1forge-quotes-api/) — Real-time bid/ask quote data for forex and cryptocurrency pairs.
- [1Forge Symbols API](https://apis.io/apis/1forge/1forge-symbols-api/) — Discover the currency pairs available to the calling API key.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [1Forge Forex Stream API](https://apis.io/asyncapis/1forge/1forge-forex-stream-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [stream](https://apis.io/channels/1forge/stream/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [1Forge Agentic Access](https://apis.io/agentic-access/1forge/1forge-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [ConversionResult](https://apis.io/schemas/1forge/forex-data-api-conversion-result/)
- [MarketStatus](https://apis.io/schemas/1forge/forex-data-api-market-status/)
- [Quota](https://apis.io/schemas/1forge/forex-data-api-quota/)
- [Quote](https://apis.io/schemas/1forge/forex-data-api-quote/)

#### JSON Structure (4)

Data models expressed in JSON Structure.

- [Forex Data Api Conversion Result Structure](https://apis.io/json-structure/1forge/forex-data-api-conversion-result-structure/)
- [Forex Data Api Market Status Structure](https://apis.io/json-structure/1forge/forex-data-api-market-status-structure/)
- [Forex Data Api Quota Structure](https://apis.io/json-structure/1forge/forex-data-api-quota-structure/)
- [Forex Data Api Quote Structure](https://apis.io/json-structure/1forge/forex-data-api-quote-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [1Forge Forex Data Api Context](https://apis.io/jsonld/1forge/1forge-forex-data-api-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [1Forge Vocabulary](https://apis.io/vocabularies/1forge/1forge-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Forex Data Api Conversion Result Example](https://apis.io/examples/1forge/forex-data-api-conversion-result-example/)
- [Forex Data Api Market Status Example](https://apis.io/examples/1forge/forex-data-api-market-status-example/)
- [Forex Data Api Quota Example](https://apis.io/examples/1forge/forex-data-api-quota-example/)
- [Forex Data Api Quote Example](https://apis.io/examples/1forge/forex-data-api-quote-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [1Forge Forex Data Convert API](https://apis.io/collections/1forge/open-1forge-convert-api/)
- [1Forge Forex Data API](https://apis.io/collections/1forge/open-1forge-forex-data-api/)
- [1Forge Forex Data Convert Market Status API](https://apis.io/collections/1forge/open-1forge-market-status-api/)
- [1Forge Forex Data Convert Quota API](https://apis.io/collections/1forge/open-1forge-quota-api/)
- [1Forge Forex Data Convert Quotes API](https://apis.io/collections/1forge/open-1forge-quotes-api/)
- [1Forge Forex Data Convert Symbols API](https://apis.io/collections/1forge/open-1forge-symbols-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [1Forge — asyncapi rules](https://apis.io/rules/1forge/1forge-asyncapi-spectral-rules/)
- [1Forge — jsonschema rules](https://apis.io/rules/1forge/1forge-jsonschema-spectral-rules/)
- [1Forge API Rules](https://apis.io/rules/1forge/1forge-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [1Forge Authentication](https://apis.io/security/1forge/1forge-authentication/)
- [1Forge Domain Security](https://apis.io/security/1forge/1forge-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [1Forge Plans Pricing](https://apis.io/plans/1forge/1forge-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [1Forge Rate Limits](https://apis.io/rate-limits/1forge/1forge-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [1Forge Finops](https://apis.io/finops/1forge/1forge-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://1forge.com)
- [Documentation](https://1forge.com/forex-data-api/api-documentation)
- [Pricing](https://1forge.com/pricing)
- [Blog](https://1forge.com/blog/)
- [Terms of service](https://1forge.com/terms)
- [GitHub](https://github.com/1Forge)

## API Evangelist rating

**Kin Score 30.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 29.9 |
| Contract governance | 27.3 |
| Operational transparency | 7.9 |
| Developer ergonomics | 31.0 |
| Access clarity | 21.1 |

**Agent readiness 27.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.3** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/1forge/](https://apis.io/providers/1forge/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for 1Forge: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/1forge/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
