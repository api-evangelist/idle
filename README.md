# Idle Finance

Idle Finance is a decentralized yield automation protocol that has operated since 2019. The platform enables users and integrators to optimize yield generation across DeFi by aggregating yield sources from protocols such as Compound, Aave, Morpho, and Clearpool. Idle supports multiple chains including Ethereum, Polygon, Polygon zkEVM, and Optimism.

The Idle Finance REST API provides programmatic access to Best Yield and Yield Tranches vault pools, total value locked (TVL) metrics per underlying token, and historical yield rates for supported token addresses. Authentication is via Bearer token, obtained by request through the developer intake form.

**Human URL:** [https://idle.finance](https://idle.finance)  
**Developer Docs:** [https://docs.idle.finance/developers/api](https://docs.idle.finance/developers/api)  
**Base URL (Ethereum):** `https://api.idle.finance`  
**Base URL (Polygon zkEVM):** `https://api-zkevm.idle.finance`  
**Base URL (Optimism):** `https://api-optimism.idle.finance`

## APIs

- **Pools** (`GET /pools`) - Returns all network pools for Best Yield and Yield Tranches vaults
- **TVLs** (`GET /tvls`) - Returns total value locked per underlying token
- **Rates** (`GET /rates/{address}`) - Returns historical daily yield data for Best Yield vaults in a given date range

## Authentication

Bearer token required for all API endpoints. Request access via:  
[https://idlefinance.typeform.com/to/CzRkDH](https://idlefinance.typeform.com/to/CzRkDH)

## Contents

| File | Description |
|------|-------------|
| `apis.yml` | APIs.json 0.19 provider profile |
| `plans/plans.yml` | API access plans and Integrators Program details |
| `rate-limits/rate-limits.yml` | Rate limit documentation |
| `finops/finops.yml` | Financial operations and cost guidance |

## Links

- [Website](https://idle.finance)
- [Documentation](https://docs.idle.finance)
- [GitHub](https://github.com/Idle-Finance)
- [Governance](https://gov.idle.finance)
- [Bug Bounty](https://immunefi.com/bounty/idlefinance/)
- [Discord](https://discord.gg/mpySAJp)
- [Twitter](https://twitter.com/idlefinance)
- [Blog](https://medium.com/idle-finance)
