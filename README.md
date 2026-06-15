# Uniswap (uniswap)

Uniswap is the world's leading decentralized exchange (DEX) protocol, enabling permissionless token swaps on Ethereum and 25+ EVM-compatible blockchains through automated market making (AMM). The Uniswap Labs Trading API provides REST endpoints for quotes, swap execution, gasless UniswapX orders, liquidity provider (LP) position management, and wallet operations. Developers can build trading bots, portfolio managers, DeFi aggregators, and embedded swap UIs on top of the protocol.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Blockchain
- Cryptocurrency
- DeFi
- Decentralized Exchange
- Liquidity
- Swaps

## Timestamps

- **Created:** 2024-12-16
- **Modified:** 2026-05-19

## APIs

### Uniswap Trading API

The Uniswap Trading API provides REST endpoints for token swaps, bridges, liquidity management, and execution planning across 25+ blockchain networks. It supports swap quoting, gasless UniswapX orders, LP position management, wallet operations (EIP-7702, ERC-4337), and multi-step execution plans. Authentication requires an API key passed in the x-api-key header.

- **Human URL:** [https://developers.uniswap.org/](https://developers.uniswap.org/)

#### Tags

- Blockchain
- Cryptocurrency
- DeFi
- Liquidity
- Swaps

#### Properties

- [Documentation](https://developers.uniswap.org/)
- [Sign Up](https://developers.uniswap.org/dashboard)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/openapi/uniswap-trading-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-quote-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-quote-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-create-swap-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-create-swap-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-order-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-schema/uniswap-order-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/examples/uniswap-get-swap-quote-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/examples/uniswap-create-swap-transaction-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/examples/uniswap-create-gasless-order-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/examples/uniswap-create-lp-position-example.json)
- [Postman Collection](collections/uniswap-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uniswap-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Uniswap Subgraph API

The Uniswap Subgraph API provides GraphQL endpoints for querying on-chain data across Uniswap protocol versions v1, v2, v3, and v4. Powered by The Graph Protocol decentralized network, it supports queries for pools, positions, swaps, ticks, and historical data. Requires an API key from The Graph Studio.

- **Human URL:** [https://developers.uniswap.org/api/overview](https://developers.uniswap.org/api/overview)

#### Tags

- Blockchain
- DeFi
- GraphQL
- On-Chain Data

#### Properties

- [Documentation](https://developers.uniswap.org/api/overview)
- [Postman Collection](collections/uniswap-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uniswap-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### UniswapX API

UniswapX is a gasless, auction-based ERC20 swap settlement protocol that routes orders through a competitive filler network. Swappers sign off-chain orders which are filled by fillers who compete to provide the best execution. The API supports order creation, retrieval, and status tracking.

- **Human URL:** [https://docs.uniswap.org/](https://docs.uniswap.org/)

#### Tags

- Blockchain
- DeFi
- Gasless
- Intent Orders

#### Properties

- [Documentation](https://docs.uniswap.org/)
- [Postman Collection](collections/uniswap-trading.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uniswap-trading.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/uniswaporg)
- [Portal](https://developers.uniswap.org/)
- [Documentation](https://docs.uniswap.org/)
- [Login](https://developers.uniswap.org/dashboard)
- [GitHub Organization](https://github.com/Uniswap)
- [Blog](https://blog.uniswap.org/)
- [Discord](https://discord.gg/FCfyBSbCU5)
- [X (Twitter)](https://twitter.com/uniswap)
- [SDK](https://www.npmjs.com/package/@uniswap/sdk-core)
- [SDK](https://www.npmjs.com/package/@uniswap/v3-sdk)
- [SDK](https://developers.uniswap.org/docs/sdks/v4/overview)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/rules/uniswap-spectral-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/vocabulary/uniswap-vocabulary.yaml)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-ld/uniswap-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://developers.uniswap.org/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
