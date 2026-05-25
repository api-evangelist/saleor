# Saleor

Saleor is an open-source, GraphQL-first headless commerce platform built in Python (Django) with a TypeScript React dashboard. The entire commerce surface — products, channels, checkout, orders, payments, promotions, taxes, attributes, and warehouses — is exposed through a single GraphQL API consumed by storefronts, the Saleor Dashboard, and third-party Saleor Apps.

- Website: https://saleor.io/
- Documentation: https://docs.saleor.io/
- API Reference: https://docs.saleor.io/api-reference/
- GitHub: https://github.com/saleor
- Saleor Cloud: https://cloud.saleor.io/
- Status: https://status.saleor.io/
- Discord: https://saleor.io/discord
- LLMs.txt: https://docs.saleor.io/llms.txt

## APIs and Components

- `saleor:graphql-api` — Saleor GraphQL API (single endpoint covering the full commerce model)
- `saleor:core-repo` — Saleor Core server (Django / Python)
- `saleor:dashboard` — Saleor Dashboard (React / TypeScript admin client)
- `saleor:storefront` — Saleor Storefront (Next.js reference storefront)
- `saleor:app-sdk` — Saleor App SDK (TypeScript)
- `saleor:app-template` — Saleor App Template (Next.js starter)
- `saleor:sdk-js` — saleor-sdk (TypeScript / JavaScript SDK)
- `saleor:cloud` — Saleor Cloud (hosted, managed offering)

## Profile Artifacts

| Artifact | Path |
|---|---|
| API index | [`apis.yml`](apis.yml) |
| OpenAPI (GraphQL transport) | [`openapi/saleor-openapi.yml`](openapi/saleor-openapi.yml) |
| Plans / Pricing (API Commons Plans 0.1) | [`plans/saleor-plans-pricing.yml`](plans/saleor-plans-pricing.yml) |
| Rate Limits (API Commons Rate Limits 0.1) | [`rate-limits/saleor-rate-limits.yml`](rate-limits/saleor-rate-limits.yml) |
| FinOps (FOCUS-aligned) | [`finops/saleor-finops.yml`](finops/saleor-finops.yml) |

## Type

`opensource` — Saleor is a BSD-licensed open-source project with a hosted commercial offering (Saleor Cloud). This profile follows the GitHub-first open-source pipeline; commercial artifacts (plans, rate limits, FinOps) are included because of the hosted Saleor Cloud offering.

## References

Profiled with assistance from Anthropic's Claude under the API Evangelist research pipeline — https://www.anthropic.com/
