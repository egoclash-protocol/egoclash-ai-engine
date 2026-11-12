# 🛡️ EgoClash (`$EGOC`) — On-Chain Security & Zero-Privilege Architecture

## 1. Zero-Key & Air-Gapped Enclave Guarantee
This public repository contains **strictly protocol specifications, mathematical standards, TypeScript interface definitions, and public smart contract source code** for external verification.

- **Zero Private Keys / Zero RPC Credentials:** No wallet keys, seed phrases, signer daemons, or proprietary AI execution weights are stored or referenced in this repository.
- **Air-Gapped Read-Only Oracle:** The proprietary EgoClash Multi-Agent Enclave interacts with the blockchain **exclusively via read-only public market telemetry** (spot price and volume). The AI agents possess **zero signing authority** over any liquidity pool, treasury wallet, or token contract.

---

## 2. Token Invariants (Solana SPL, mint `BrfMCtwXY7tLvgmPD2wFk55ckvFms2MVNrzu1yZBpump`)

| Security Vector | Standard / Configuration | Verification Status |
| :--- | :--- | :--- |
| **Supply** | Initial `1,000,000,000 $EGOC`; current on-chain supply is lower because tokens have been burned | Mint account `supply` on [Solscan](https://solscan.io/token/BrfMCtwXY7tLvgmPD2wFk55ckvFms2MVNrzu1yZBpump) |
| **Mint Authority** | `null` (revoked) | Cannot mint new tokens |
| **Freeze Authority** | `null` (revoked) | No wallet can be frozen |
| **Buy / Sell Tax** | `0.0% / 0.0%` | Creator fees: pump.fun creator rewards are paid to the creator-rewards wallet; the protocol adds no extra fees |
