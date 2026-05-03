# Uniswap (uniswap)
Uniswap is the world's leading decentralized exchange (DEX) protocol, enabling permissionless token swaps on Ethereum and 25+ EVM-compatible blockchains through automated market making (AMM). The Uniswap Labs Trading API provides REST endpoints for quotes, swap execution, gasless UniswapX orders, liquidity provider (LP) position management, and wallet operations. Developers can build trading bots, portfolio managers, DeFi aggregators, and embedded swap UIs on top of the protocol.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Blockchain, Cryptocurrency, DeFi, Decentralized Exchange, Liquidity, Swaps

## Timestamps

- **Created:** 2024-12-16
- **Modified:** 2026-05-03

## APIs

### Uniswap Trading API
The Uniswap Trading API provides REST endpoints for token swaps, bridges, liquidity management, and execution planning across 25+ blockchain networks. It supports swap quoting, gasless UniswapX orders, LP position management, wallet operations (EIP-7702, ERC-4337), and multi-step execution plans. Authentication requires an API key passed in the x-api-key header.

**Human URL:** [https://developers.uniswap.org/](https://developers.uniswap.org/)

#### Tags:

 - Blockchain, Cryptocurrency, DeFi, Liquidity, Swaps

#### Properties

- [Documentation](https://developers.uniswap.org/)
- [Sign Up](https://developers.uniswap.org/dashboard)
- [OpenAPI](openapi/uniswap-trading-openapi.yaml)
- [JSON Schema - Quote Request](json-schema/uniswap-quote-request-schema.json)
- [JSON Schema - Quote Response](json-schema/uniswap-quote-response-schema.json)
- [JSON Schema - Create Swap Request](json-schema/uniswap-create-swap-request-schema.json)
- [JSON Schema - Create Swap Response](json-schema/uniswap-create-swap-response-schema.json)
- [JSON Schema - Order Request](json-schema/uniswap-order-request-schema.json)
- [JSON Schema - Order Response](json-schema/uniswap-order-response-schema.json)
- [Example - Get Swap Quote](examples/uniswap-get-swap-quote-example.json)
- [Example - Create Swap Transaction](examples/uniswap-create-swap-transaction-example.json)
- [Example - Create Gasless Order](examples/uniswap-create-gasless-order-example.json)
- [Example - Create LP Position](examples/uniswap-create-lp-position-example.json)

### Uniswap Subgraph API
The Uniswap Subgraph API provides GraphQL endpoints for querying on-chain data across Uniswap protocol versions v1, v2, v3, and v4. Powered by The Graph Protocol decentralized network, it supports queries for pools, positions, swaps, ticks, and historical data. Requires an API key from The Graph Studio.

**Human URL:** [https://developers.uniswap.org/api/overview](https://developers.uniswap.org/api/overview)

#### Tags:

 - Blockchain, DeFi, GraphQL, On-Chain Data

#### Properties

- [Documentation](https://developers.uniswap.org/api/overview)

### UniswapX API
UniswapX is a gasless, auction-based ERC20 swap settlement protocol that routes orders through a competitive filler network. Swappers sign off-chain orders which are filled by fillers who compete to provide the best execution. The API supports order creation, retrieval, and status tracking.

**Human URL:** [https://docs.uniswap.org/](https://docs.uniswap.org/)

#### Tags:

 - Blockchain, DeFi, Gasless, Intent Orders

#### Properties

- [Documentation](https://docs.uniswap.org/)

## Common Properties

- [Portal](https://developers.uniswap.org/)
- [Documentation](https://docs.uniswap.org/)
- [Login](https://developers.uniswap.org/dashboard)
- [GitHub Organization](https://github.com/Uniswap)
- [Blog](https://blog.uniswap.org/)
- [Discord](https://discord.gg/FCfyBSbCU5)
- [X](https://twitter.com/uniswap)
- [SDK - Core TypeScript](https://www.npmjs.com/package/@uniswap/sdk-core)
- [SDK - v3 TypeScript](https://www.npmjs.com/package/@uniswap/v3-sdk)
- [SDK - v4 TypeScript](https://developers.uniswap.org/docs/sdks/v4/overview)
- [Spectral Rules](rules/uniswap-spectral-rules.yml)
- [Vocabulary](vocabulary/uniswap-vocabulary.yaml)
- [Naftiko Capability](capabilities/defi-trading.yaml)
- [JSON-LD Context](json-ld/uniswap-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Token Swaps | Swap any ERC-20 token on 25+ EVM chains with optimal routing across Uniswap v2, v3, and v4 liquidity pools. |
| Gasless UniswapX Orders | Sign off-chain intent-based orders that are filled by competing fillers without requiring the swapper to pay gas fees directly. |
| Liquidity Provider Management | Create, increase, decrease, and manage concentrated liquidity positions on Uniswap v3 and v4 with fee tier and tick range control. |
| Cross-Chain Bridging | Bridge tokens across EVM networks using the unified quote and swap APIs with automatic routing to the best bridge provider. |
| Limit Orders | Submit limit orders that execute automatically when market conditions meet the specified price target. |
| Smart Wallet Support | Native support for EIP-7702 delegated accounts, ERC-4337 account abstraction, and EIP-5792 wallet capabilities. |
| Execution Plans | Create multi-step execution plans for complex DeFi workflows with step proofs for verification and tracking. |
| On-Chain Data via Subgraphs | Query historical and real-time on-chain data for pools, positions, swaps, and ticks via GraphQL subgraph endpoints. |

## Use Cases

| Name | Description |
|------|-------------|
| Token Swap Integration | Embed token swap functionality in wallets, DApps, and portfolio managers using the Trading API's quote and swap endpoints. |
| DeFi Aggregator | Build a DEX aggregator that routes through Uniswap's liquidity alongside other protocols for best execution. |
| Liquidity Mining Bot | Automate LP position management — create, rebalance, and close positions based on market conditions using LP management endpoints. |
| On-Chain Analytics | Power analytics dashboards with historical pool, swap, and liquidity data from the Subgraph GraphQL API. |
| Cross-Chain Bridge UI | Build a bridge interface that quotes and executes cross-chain token transfers using the swap/bridge endpoints. |

## Integrations

| Name | Description |
|------|-------------|
| The Graph Protocol | Uniswap subgraphs are indexed and served by The Graph Protocol's decentralized network. |
| Ethereum | Primary deployment network for Uniswap v2, v3, and v4 smart contracts. |
| Polygon | Uniswap v3 deployed on Polygon PoS and zkEVM networks. |
| Arbitrum | Uniswap v3 deployed on Arbitrum One for low-cost swaps. |
| Optimism | Uniswap v3 deployed on Optimism for low-cost swaps. |
| Base | Uniswap v3 and v4 deployed on Base (Coinbase's L2 network). |
| UniswapX Fillers | Third-party filler bots compete to fill UniswapX gasless orders for best execution. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Uniswap Trading API](openapi/uniswap-trading-openapi.yaml)

### JSON Schema

- [Quote Request](json-schema/uniswap-quote-request-schema.json)
- [Quote Response](json-schema/uniswap-quote-response-schema.json)
- [Create Swap Request](json-schema/uniswap-create-swap-request-schema.json)
- [Create Swap Response](json-schema/uniswap-create-swap-response-schema.json)
- [Order Request](json-schema/uniswap-order-request-schema.json)
- [Order Response](json-schema/uniswap-order-response-schema.json)
- [Limit Order Quote Request](json-schema/uniswap-limit-order-quote-request-schema.json)
- [Limit Order Quote Response](json-schema/uniswap-limit-order-quote-response-schema.json)
- [Get Orders Response](json-schema/uniswap-get-orders-response-schema.json)
- [Get Swaps Response](json-schema/uniswap-get-swaps-response-schema.json)
- [User Operation](json-schema/uniswap-user-operation-schema.json)
- [Create Position Request](json-schema/uniswap-create-position-request-schema.json)
- [Swap Status](json-schema/uniswap-swap-status-schema.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Uniswap Trading API](capabilities/shared/trading-api.yaml) — 14 operations for token swaps, LP management, and execution planning

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [DeFi Trading](capabilities/defi-trading.yaml) | Uniswap Trading API | 14 | DeFi Developer, Trading Bot Engineer, LP Manager |

## Vocabulary

- [Uniswap Vocabulary](vocabulary/uniswap-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 8 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Uniswap Spectral Rules](rules/uniswap-spectral-rules.yml) — 30 rules across 9 categories enforcing Uniswap API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
