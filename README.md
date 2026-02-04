# RLP Vault (/docs/risex/features/rlp-vault)

import { Callout } from 'fumadocs-ui/components/callout';

## Overview

The RLP (RISE Liquidity Provider) Vault is RISEx's protocol-owned market making vault. It allows anyone to deposit and earn yield from professional market making strategies.

RLP is an **ERC-4626 vault**, meaning your vault shares are standard tokens that can be used freely across DeFi as collateral, in yield strategies, or anywhere ERC-20s are accepted.

***

## How It Works

1. **Deposit** USDC into the vault
2. **Receive** vault shares (ERC-4626 standard)
3. **Earn** yield as the vault operates
4. **Withdraw** when ready (subject to withdrawal queue)

Your vault shares represent your proportional ownership of the vault's assets and earnings.

***

## Revenue Sources

The vault generates returns through multiple strategies:

| Source            | Description                                               |
| ----------------- | --------------------------------------------------------- |
| **Market Making** | Providing liquidity on the orderbook across trading pairs |
| **Liquidations**  | First-look access to liquidation opportunities            |

Returns are variable based on market conditions and vault performance.

***

## DeFi Composability

Because RLP uses the ERC-4626 standard, your vault shares are fully composable:

* **Use as collateral** in lending protocols
* **Loop your RLP position** to boost yield
* **Provide liquidity** in DEX pools
* **Integrate into yield strategies** and vaults-of-vaults
* **Transfer freely** like any ERC-20 token

This is impossible with siloed vault systems. On RISEx, your market making position is a liquid, programmable asset.

***

## Withdrawal Queue

Withdrawals are processed through a queue to ensure vault stability. This protects against scenarios where sudden mass withdrawals could force the vault to close positions at unfavorable prices.

***

## Risk Disclosure

Vault depositors share in market making risk. The vault may experience losses during:

* Extreme market volatility
* Adverse price movements
