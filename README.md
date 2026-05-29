# 1Forge (1forge)

1Forge delivers real-time forex and cryptocurrency quotes for 700+ currency pairs through a simple JSON REST API and a low-latency WebSocket stream. The product targets trading apps, multi-currency checkout flows, treasury and FinOps tooling, and any workload that needs FIX-speed price data without the FIX-grade integration cost.

**URL:** [Visit APIs.json URL](https://1forge.com/forex-data-api/api-documentation)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Currency Exchange, Forex, Cryptocurrency, Market Data, Financial Data, Real-Time Data

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-28

## APIs

### 1Forge Forex Data API

Real-time bid/ask quote retrieval, currency conversion, symbol discovery, market status, and quota inspection for 700+ forex and cryptocurrency pairs served from four global edges (Oregon, Virginia, Taiwan, Belgium).

**Human URL:** [https://1forge.com/forex-data-api/api-documentation](https://1forge.com/forex-data-api/api-documentation)

#### Tags:

 - Currency Exchange, Forex, Cryptocurrency, Market Data, REST

#### Properties

- [Documentation](https://1forge.com/forex-data-api/api-documentation)
- [OpenAPI](openapi/1forge-forex-data-api.yml)
- [JavaScript SDK](https://github.com/1Forge/javascript-forex-quotes)
- [PHP SDK](https://github.com/1Forge/php-forex-quotes)
- [Python SDK](https://github.com/1Forge/python-forex-quotes)
- [Java SDK](https://github.com/1Forge/java-forex-quotes)
- [Go SDK](https://github.com/1Forge/golang-forex-quotes)
- [.NET SDK](https://github.com/1Forge/dotnet-forex-quotes)
- [Naftiko Capability — Quotes](capabilities/forex-data-api-quotes.yaml)
- [Naftiko Capability — Convert](capabilities/forex-data-api-convert.yaml)
- [Naftiko Capability — Symbols](capabilities/forex-data-api-symbols.yaml)
- [Naftiko Capability — Market Status](capabilities/forex-data-api-market-status.yaml)
- [Naftiko Capability — Quota](capabilities/forex-data-api-quota.yaml)

### 1Forge Forex Stream

WebSocket stream that delivers real-time bid/ask updates for subscribed forex and cryptocurrency pairs. Streaming is gated to paid plans.

**Human URL:** [https://1forge.com/forex-data-api/api-documentation](https://1forge.com/forex-data-api/api-documentation)

#### Tags:

 - Currency Exchange, Forex, Cryptocurrency, Market Data, WebSocket, Streaming

#### Properties

- [Documentation](https://1forge.com/forex-data-api/api-documentation)
- [AsyncAPI](asyncapi/1forge-forex-stream-asyncapi.yml)
- [JavaScript SDK (WebSocket)](https://github.com/1Forge/javascript-forex-quotes)
- [PHP SDK (WebSocket)](https://github.com/1Forge/php-forex-quotes)

## Common Properties

- [Website](https://1forge.com)
- [Documentation](https://1forge.com/forex-data-api/api-documentation)
- [SignUp](https://1forge.com/register)
- [Pricing](https://1forge.com/pricing)
- [TermsOfService](https://1forge.com/terms)
- [GitHubOrganization](https://github.com/1Forge)
- [Plans](plans/1forge-plans-pricing.yml)
- [RateLimits](rate-limits/1forge-rate-limits.yml)
- [FinOps](finops/1forge-finops.yml)
- [Vocabulary](vocabulary/1forge-vocabulary.yml)
- [SpectralRules](rules/1forge-rules.yml)
- [JSONLD](json-ld/1forge-forex-data-api-context.jsonld)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)

## Features

| Name | Description |
|------|-------------|
| Real-Time Forex Quotes | Bid/ask snapshots for 700+ currency pairs with sub-second updates direct from brokers and liquidity providers. |
| Cryptocurrency Quotes | Crypto pair coverage alongside traditional forex pairs via the same REST and WebSocket surfaces. |
| Currency Conversion | Single-call conversion of an amount between two currencies at the current market rate. |
| WebSocket Streaming | Real-time price-update stream over a single persistent WebSocket connection; available on paid plans. |
| Synthetic Pair Coverage | Both organic (direct from exchanges) and synthetic (best-rate cross-pair) currency pairs. |
| Per-Key Quota Inspection | GET /quota returns quota_used, quota_limit, quota_remaining, and hours_until_reset for the calling key. |
| Multi-Region Edge | Requests are auto-routed to one of four global edges (Oregon, Virginia, Taiwan, Belgium) for lowest latency. |
| Multi-Language SDKs | Official client libraries in JavaScript, PHP, Python, Java, Go, and .NET. |

## Use Cases

| Name | Description |
|------|-------------|
| Multi-Currency Checkout | Convert cart totals to a customer's local currency at checkout using the /convert endpoint. |
| Trading App Pricing Display | Drive real-time ticker UIs for retail trading and portfolio apps via REST polling or the WebSocket stream. |
| Treasury and Reconciliation | Stamp daily reconciliation reports with mid-market FX rates for cross-border ledger entries. |
| FX Risk and Hedging Analytics | Feed live bid/ask data into hedging and FX-exposure dashboards. |
| Quota and Cost Telemetry | Track per-key quota burn into observability and FinOps pipelines via GET /quota. |

## Integrations

| Name | Description |
|------|-------------|
| JavaScript / TypeScript Apps | First-party forex-quotes npm library covering REST and WebSocket access. |
| PHP Applications | Official PHP library with REST and WebSocket support. |
| Python Applications | Official Python library for REST quote retrieval. |
| Java Applications | Official Java library for REST quote retrieval. |
| Go Applications | Official Go library for REST quote retrieval. |
| .NET Applications | Official .NET (C#) library for REST quote retrieval. |

## Solutions

| Name | Description |
|------|-------------|
| Brokerage and Trading Platforms | FIX-grade speed at JSON-API cost for retail brokerages and options houses. |
| Fintech Apps and Wallets | Live FX quotes for consumer wallets, neobanks, and remittance apps. |
| Ecommerce Multi-Currency Pricing | Currency conversion and live rates for international checkout flows. |
| Analytics and BI Tools | Bid/ask history capture (client-side) and conversion rates for financial dashboards. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [1Forge Forex Data API](openapi/1forge-forex-data-api.yml)

### AsyncAPI

- [1Forge Forex Stream](asyncapi/1forge-forex-stream-asyncapi.yml)

### JSON Schema

- [Quote](json-schema/forex-data-api-quote-schema.json)
- [ConversionResult](json-schema/forex-data-api-conversion-result-schema.json)
- [MarketStatus](json-schema/forex-data-api-market-status-schema.json)
- [Quota](json-schema/forex-data-api-quota-schema.json)

### JSON Structure

- [Quote](json-structure/forex-data-api-quote-structure.json)
- [ConversionResult](json-structure/forex-data-api-conversion-result-structure.json)
- [MarketStatus](json-structure/forex-data-api-market-status-structure.json)
- [Quota](json-structure/forex-data-api-quota-structure.json)

### JSON-LD

- [1Forge Forex Data API Context](json-ld/1forge-forex-data-api-context.jsonld)

### Examples

- [Quote example](examples/forex-data-api-quote-example.json)
- [ConversionResult example](examples/forex-data-api-conversion-result-example.json)
- [MarketStatus example](examples/forex-data-api-market-status-example.json)
- [Quota example](examples/forex-data-api-quota-example.json)

## Capabilities

Naftiko capabilities organized as self-contained per-tag files. Each file exposes one REST adapter and one MCP adapter routed through its own inline `consumes` block.

### 1Forge Forex Data API

| Capability | Operations | Tools |
|------------|-----------:|------:|
| [Quotes](capabilities/forex-data-api-quotes.yaml) | 1 | 1 |
| [Convert](capabilities/forex-data-api-convert.yaml) | 1 | 1 |
| [Symbols](capabilities/forex-data-api-symbols.yaml) | 1 | 1 |
| [Market Status](capabilities/forex-data-api-market-status.yaml) | 1 | 1 |
| [Quota](capabilities/forex-data-api-quota.yaml) | 1 | 1 |

## Vocabulary

- [1Forge Vocabulary](vocabulary/1forge-vocabulary.yml) — Unified taxonomy mapping 6 resources, 6 actions, 5 workflows, and 6 personas across operational (OpenAPI + AsyncAPI) and capability (Naftiko) dimensions.

## Rules

- [1Forge Spectral Rules](rules/1forge-rules.yml) — 27 rules across 11 categories enforcing 1Forge API conventions.

## Plans, Rate Limits, and FinOps

- [Plans and Pricing](plans/1forge-plans-pricing.yml) — Starter / Premium / Business / Business Plus subscription tiers.
- [Rate Limits](rate-limits/1forge-rate-limits.yml) — Per-key monthly quota plus WebSocket session gating.
- [FinOps](finops/1forge-finops.yml) — FOCUS-aligned billing model and metering surface.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
