# Saleor (saleor)

Saleor is an open-source, GraphQL-first commerce platform built in Python (Django) with a TypeScript dashboard. The entire commerce surface is exposed through a single GraphQL API used by storefronts, the Saleor Dashboard, and third-party Saleor Apps; mutations and queries cover products, channels, carts (checkout), orders, payments, promotions, taxes, attributes, and warehouses. Developer surface includes Saleor Cloud, the Saleor App SDK and App Template, a starter storefront, language SDKs (saleor-sdk for TS/JS), and an App Store of first-party and partner integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/saleor/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/saleor/refs/heads/main/apis.yml)

## Tags

- Commerce
- Headless
- eCommerce
- GraphQL
- Open Source
- Python
- TypeScript

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Saleor GraphQL API

Single GraphQL endpoint exposing the entire Saleor commerce model - products, variants, categories, collections, channels, checkout, orders, payments, promotions, taxes, attributes, warehouses, and users. Used by storefronts, the Saleor Dashboard, and installed Apps. Cloud instances expose this endpoint at /graphql/ on the API host for the store.

- **Human URL:** [https://docs.saleor.io/api-reference/](https://docs.saleor.io/api-reference/)
- **Base URL:** `https://docs.saleor.io/api-reference/`

#### Tags

- GraphQL
- Commerce
- Storefront
- Admin

#### Properties

- [Documentation](https://docs.saleor.io/api-reference/)
- [A P I  Usage](https://docs.saleor.io/api-usage/overview)
- [Postman Collection](collections/saleor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/saleor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Saleor App SDK

TypeScript SDK for building Saleor Apps - background services that extend Saleor over the GraphQL API and react to webhooks. Handles app installation, auth, async webhooks, and metadata.

- **Human URL:** [https://github.com/saleor/saleor-app-sdk](https://github.com/saleor/saleor-app-sdk)
- **Base URL:** `https://github.com/saleor/saleor-app-sdk`

#### Tags

- SDK
- TypeScript
- Apps
- Webhooks

#### Properties

- [Repository](https://github.com/saleor/saleor-app-sdk)
- [Postman Collection](collections/saleor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/saleor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Saleor App Template

Reference Next.js project for bootstrapping a Saleor App - install flow, webhook handlers, GraphQL clients, and a config UI mounted inside the Saleor Dashboard via the App Bridge.

- **Human URL:** [https://github.com/saleor/saleor-app-template](https://github.com/saleor/saleor-app-template)
- **Base URL:** `https://github.com/saleor/saleor-app-template`

#### Tags

- Starter
- Apps
- Next.js

#### Properties

- [Repository](https://github.com/saleor/saleor-app-template)
- [Postman Collection](collections/saleor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/saleor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### saleor-sdk (TypeScript / JavaScript)

Official TypeScript / JavaScript SDK wrapping the Saleor GraphQL API for storefronts and Apps - typed operations, auth, cart, and checkout helpers.

- **Human URL:** [https://github.com/saleor/saleor-sdk](https://github.com/saleor/saleor-sdk)
- **Base URL:** `https://github.com/saleor/saleor-sdk`

#### Tags

- SDK
- JavaScript
- TypeScript
- Storefront

#### Properties

- [Repository](https://github.com/saleor/saleor-sdk)
- [Postman Collection](collections/saleor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/saleor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Saleor Storefront (Next.js Starter)

Reference Next.js storefront talking to the Saleor GraphQL API - product browse, cart, checkout, account, and payments. Used as the canonical starting point for headless storefronts on Saleor.

- **Human URL:** [https://github.com/saleor/storefront](https://github.com/saleor/storefront)
- **Base URL:** `https://github.com/saleor/storefront`

#### Tags

- Storefront
- Next.js
- Starter

#### Properties

- [Repository](https://github.com/saleor/storefront)
- [Postman Collection](collections/saleor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/saleor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Saleor Dashboard

Official React / TypeScript admin dashboard for Saleor - a thick client built entirely against the Saleor GraphQL API.

- **Human URL:** [https://github.com/saleor/saleor-dashboard](https://github.com/saleor/saleor-dashboard)
- **Base URL:** `https://github.com/saleor/saleor-dashboard`

#### Tags

- Dashboard
- Admin
- React

#### Properties

- [Repository](https://github.com/saleor/saleor-dashboard)
- [Postman Collection](collections/saleor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/saleor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Saleor Cloud

Hosted, managed Saleor service - provisions Saleor cores per store with the same GraphQL API surface, plus environment management, deploys, and Apps marketplace.

- **Human URL:** [https://cloud.saleor.io/](https://cloud.saleor.io/)
- **Base URL:** `https://cloud.saleor.io/`

#### Tags

- Cloud
- Hosted
- SaaS

#### Properties

- [Application](https://cloud.saleor.io/)
- [Postman Collection](collections/saleor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/saleor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Saleor Core (Server) Repository

Source repository for the Saleor server - the Django / Python backend that implements the GraphQL API, business logic, persistence, and webhooks.

- **Human URL:** [https://github.com/saleor/saleor](https://github.com/saleor/saleor)
- **Base URL:** `https://github.com/saleor/saleor`

#### Tags

- Open Source
- Server
- Python
- Django

#### Properties

- [Repository](https://github.com/saleor/saleor)
- [Postman Collection](collections/saleor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/saleor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://saleor.io/)
- [Documentation](https://docs.saleor.io/)
- [A P I  Reference](https://docs.saleor.io/api-reference/)
- [Git Hub](https://github.com/saleor)
- [Cloud](https://cloud.saleor.io/)
- [Discord](https://saleor.io/discord)
- [Status](https://status.saleor.io/)
- [LinkedIn](https://www.linkedin.com/company/saleor-commerce/)
- [L L Ms Txt](https://docs.saleor.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
