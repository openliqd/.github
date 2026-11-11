<p align="center">
  <img src="https://raw.githubusercontent.com/openliqd/.github/main/assets/x-banner.png" alt="OpenLiqd — Be the market. Original X banner." width="100%" />
</p>

<p align="center">
  <a href="https://openliqd.com">Website</a> &nbsp; · &nbsp;
  <a href="https://x.com/openliqd">Follow on X</a> &nbsp; · &nbsp;
  <a href="https://github.com/orgs/openliqd/repositories">Explore repositories</a>
</p>

## Liquidity starts in your wallet

OpenLiqd is building onchain liquidity infrastructure powered by assets held in provider wallets. Providers authorize how their inventory can participate in swaps, and the protocol coordinates execution across eligible wallets.

Our goal is simple: make it easier to participate in onchain markets with the assets you already hold.

### How it works

| <img src="https://raw.githubusercontent.com/openliqd/.github/main/assets/icons/candles.svg" width="32" height="32" alt="" /><br />Your inventory | <img src="https://raw.githubusercontent.com/openliqd/.github/main/assets/icons/sliders.svg" width="32" height="32" alt="" /><br />Your permissions | <img src="https://raw.githubusercontent.com/openliqd/.github/main/assets/icons/swap.svg" width="32" height="32" alt="" /><br />Onchain settlement |
| :----------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| Assets stay in your wallet until an authorized swap uses them.                                                                                   | Provider policies define the conditions under which your inventory can trade.                                                                      | The protocol selects eligible providers and settles the swap onchain.                                                                             |

Published liquidity is a view of available inventory, not a reservation of funds. Execution still depends on current balances and valid authorization.

### What we're building

**EVM liquidity infrastructure**

Wallet-based liquidity, provider policies and swap execution using Calibur and EIP-7702. Current development focuses on Elysium, with Base used for additional regression testing.

**Solana research and development**

A native implementation exploring wallet-held liquidity and onchain markets within Solana's execution constraints.

**Developer experience**

Documentation and integration tooling to make these mechanisms understandable and usable.

### Development status

OpenLiqd is under active development. Local tests and fork experiments inform the design; they do not establish production readiness. A public protocol launch and independent security review remain pending.

### Follow the work

Follow [@openliqd](https://x.com/openliqd) for project updates. As repositories and research are published, they will appear here. For contributions to a public repository, start with its contribution guide and documented scope.
