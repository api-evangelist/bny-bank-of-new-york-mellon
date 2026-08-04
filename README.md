# BNY (Bank of New York Mellon) (bny-bank-of-new-york-mellon)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

BNY (rebranded from BNY Mellon in 2024, NYSE ticker changed from BK to BNY in May 2026) is the world's largest custodian bank, overseeing approximately $59.4 trillion in assets under custody and/or administration and $2.1 trillion in assets under management as of Q1 2026. BNY operates across Securities Services, Market & Wealth Services, and Investment & Wealth Management, with brand families including Pershing (clearing and custody for wealth managers, parent of NetX360+ and the Wove platform), Eagle Investment Systems (investment data management), Albridge (wealth data aggregation), BNY Markets (FX, securities finance, capital markets), and BNY Investments. BNY publishes APIs through the BNY Developer Marketplace at developer.bny.com (formerly marketplace.bnymellon.com), covering Asset Servicing, Treasury Services, Payments, Pershing, Markets, and the BNY Data On-Chain product, with registration and API reference gated behind a Nexen single sign-on.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bny-bank-of-new-york-mellon/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bny-bank-of-new-york-mellon/refs/heads/main/apis.yml)

## Tags

- Banking
- Custody
- Asset Servicing
- Treasury Services
- Payments
- Wealth Management
- Clearing
- Capital Markets
- Digital Assets
- Financial Services

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### BNY Asset Servicing API

BNY Asset Servicing APIs expose the firm's custody, fund accounting, middle-office, transfer agency, ETF servicing, and data & analytics surface to institutional clients through the BNY Developer Marketplace. Asset Servicing is anchored by approximately $59.4 trillion in assets under custody and/or administration (Q1 2026) and underpins BNY's positioning as the world's largest custodian.

- **Human URL:** [https://developer.bny.com/](https://developer.bny.com/)
- **Base URL:** `https://apigateway.bny.com`

#### Tags

- Asset Servicing
- Custody
- Fund Accounting
- Middle Office
- Data And Analytics

#### Properties

- [Documentation](https://developer.bny.com/)
- [Sign Up](https://developer.bny.com/)
- [Sandbox](https://apigateway.qa.bny.com)
- [OpenAPI](openapi/bny-asset-servicing-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bny-asset-servicing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bny-asset-servicing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BNY Treasury Services API

BNY Treasury Services APIs cover payments (USD clearing, global ACH, RTP, wires, Pay by Bank / open banking), liquidity, cash management, trade finance, and FX. BNY is one of the largest USD clearers in the world and exposes these capabilities to corporate, FI, and fintech clients through the BNY Developer Marketplace.

- **Human URL:** [https://developer.bny.com/](https://developer.bny.com/)
- **Base URL:** `https://apigateway.bny.com`

#### Tags

- Treasury Services
- Payments
- Cash Management
- Liquidity
- Trade Finance
- Foreign Exchange
- Open Banking

#### Properties

- [Documentation](https://developer.bny.com/)
- [Sign Up](https://developer.bny.com/)
- [Sandbox](https://apigateway.qa.bny.com)
- [OpenAPI](openapi/bny-treasury-services-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bny-treasury-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bny-treasury-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BNY Pershing API

BNY Pershing APIs expose the Pershing clearing and custody platform — NetX360+ for advisors and the Wove wealth platform — to broker-dealers, RIAs, and wealth technology partners. Surface includes account opening, brokerage operations, positions and balances, statements, and integrations with the broader Wove ecosystem (planning, billing, performance, model marketplace).

- **Human URL:** [https://developer.bny.com/](https://developer.bny.com/)
- **Base URL:** `https://apigateway.bny.com`

#### Tags

- Pershing
- Wealth Management
- Clearing
- Custody
- Brokerage
- NetX360
- Wove

#### Properties

- [Documentation](https://developer.bny.com/)
- [Sign Up](https://developer.bny.com/)
- [Sandbox](https://apigateway.qa.bny.com)
- [OpenAPI](openapi/bny-pershing-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bny-pershing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bny-pershing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BNY Markets API

BNY Markets APIs expose FX, securities finance (agency lending, collateral, repo), and fixed income / equities execution to institutional clients through the BNY Developer Marketplace. Markets sits inside the Market & Wealth Services segment alongside Pershing and Treasury Services.

- **Human URL:** [https://developer.bny.com/](https://developer.bny.com/)
- **Base URL:** `https://apigateway.bny.com`

#### Tags

- Capital Markets
- Foreign Exchange
- Securities Finance
- Collateral
- Repo
- Fixed Income
- Equities

#### Properties

- [Documentation](https://developer.bny.com/)
- [Sign Up](https://developer.bny.com/)
- [Sandbox](https://apigateway.qa.bny.com)
- [OpenAPI](openapi/bny-markets-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bny-markets-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bny-markets-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BNY Data On-Chain

BNY Data On-Chain publishes BNY-attested data on-chain so on-chain consumers can read it directly from smart contracts. The product ships a Solidity consumer interface (IBNYDataConsumerV2) with typed accessors (getType, getUint256, getInt256, getBytes32, getString32) and is deployed on Ethereum Mainnet and Sepolia testnet. The user guide repository is the canonical public artifact.

- **Human URL:** [https://github.com/bnymellon/bny-data-on-chain](https://github.com/bnymellon/bny-data-on-chain)
- **Base URL:** `https://etherscan.io/address/0x7B0eC8D1D1254358A77f107118e96885EdDCEb16`

#### Tags

- Digital Assets
- Blockchain
- Ethereum
- Smart Contracts
- Oracle
- Tokenization

#### Properties

- [Documentation](https://github.com/bnymellon/bny-data-on-chain)
- [Source Code](https://github.com/bnymellon/bny-data-on-chain)
- [Smart Contract](https://etherscan.io/address/0x7B0eC8D1D1254358A77f107118e96885EdDCEb16)
- [Testnet](https://sepolia.etherscan.io/address/0xCC75D07cBC86f306A033af29508a1b98E2178264)
- [Postman Collection](collections/bny-asset-servicing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bny-asset-servicing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/bny-markets-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bny-markets-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/bny-pershing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bny-pershing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/bny-treasury-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bny-treasury-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.bny.com)
- [Developer Portal](https://developer.bny.com)
- [GitHub Organization](https://github.com/bnymellon)
- [About](https://www.bny.com/corporate/global/en/about-us.html)
- [Newsroom](https://www.bny.com/corporate/global/en/newsroom.html)
- [Insights](https://www.bny.com/corporate/global/en/insights/all-insights.html)
- [Investor Relations](https://www.bny.com/investor-relations.html)
- [LinkedIn](https://www.linkedin.com/company/the-bank-of-new-york-mellon-corporation)
- [Wikipedia](https://en.wikipedia.org/wiki/BNY)
- [Plans](plans/bny-bank-of-new-york-mellon-plans-pricing.yml)
- [Rate Limits](rate-limits/bny-bank-of-new-york-mellon-rate-limits.yml)
- [Fin Ops](finops/bny-bank-of-new-york-mellon-finops.yml)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
