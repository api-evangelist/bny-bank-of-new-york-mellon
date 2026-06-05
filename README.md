# BNY (Bank of New York Mellon) (bny-bank-of-new-york-mellon)

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
