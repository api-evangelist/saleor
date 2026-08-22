# Saleor (saleor)

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
