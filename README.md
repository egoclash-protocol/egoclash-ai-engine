<p align="center">
  <img src="./assets/egoc_logo.png" alt="EgoClash ($EGOC) Official Protocol Logo" width="220" style="border-radius: 14px;" />
</p>

# 🧠 EgoClash Protocol (`$EGOC`)
### Official Protocol Specifications, Mathematical Standards (`PVSE v1.2`) & Smart Contracts

[![Ticker](https://img.shields.io/badge/Ticker-%24EGOC-15803d?style=for-the-badge)](./WHITEPAPER.md)
[![Whitepaper](https://img.shields.io/badge/Read-Protocol_Whitepaper_v2.1-111827?style=for-the-badge)](./WHITEPAPER.md)
[![Network](https://img.shields.io/badge/Network-Solana-9945FF?style=for-the-badge)](https://pump.fun/coin/BrfMCtwXY7tLvgmPD2wFk55ckvFms2MVNrzu1yZBpump)
[![Pump.fun](https://img.shields.io/badge/Pump.fun-%24EGOC_Live-10B981?style=for-the-badge)](https://pump.fun/coin/BrfMCtwXY7tLvgmPD2wFk55ckvFms2MVNrzu1yZBpump)
[![X](https://img.shields.io/badge/X-%40EgoClash__EGOC-000000?style=for-the-badge)](https://x.com/EgoClash_EGOC)
[![Telegram](https://img.shields.io/badge/Telegram-t.me%2FEgoClash__EGOC-26A5E4?style=for-the-badge)](https://t.me/EgoClash_EGOC)

This repository contains the **official Protocol Whitepaper v2.1, technical standards, mathematical specifications, TypeScript SDK interfaces, and verifiable smart contracts** for the **EgoClash (`$EGOC`)** protocol on Solana.

> **Contract Address (Solana CA):** `BrfMCtwXY7tLvgmPD2wFk55ckvFms2MVNrzu1yZBpump`

> **Proprietary IP & Security Notice:** To protect the protocol's intellectual property against sybil cloning and prompt extraction, the live **Multi-Agent Execution Enclave**, neural prompt weights, and SFT training datasets are operated strictly as a **closed-source private enclave**. The enclave interacts with on-chain state exclusively via read-only public spot telemetry and holds zero private keys or signing privileges.

---

## 📂 Repository Contents (Public Standards & Verifiable Contracts)

| Directory / File | Description |
| :--- | :--- |
| [**`WHITEPAPER.md`**](./WHITEPAPER.md) | **Official Protocol Whitepaper v2.1:** the cast, how the desk publishes, the canon, and on-chain-verified token facts (supply, authorities, dev buy, Jupiter Lock), each with a link to check it. |
| [**`specs/PVSE_MATHEMATICAL_STANDARD.md`**](./specs/PVSE_MATHEMATICAL_STANDARD.md) | **EGOC-SPEC-001:** Formal mathematical specification of the *Pre-Publication Virality & Spot-Truth Scoring Engine (`PVSE v1.2`)*. |
| [**`specs/MULTI_AGENT_PROTOCOL_STANDARD.md`**](./specs/MULTI_AGENT_PROTOCOL_STANDARD.md) | **EGOC-SPEC-002:** Technical standard for *Asynchronous Multi-Agent Dialectical Consensus, Non-Homogeneous Poisson Pacing, and Strategic Silence ($\varnothing$)*. |
| [**`contracts/EgoClashERC20.sol`**](./contracts/EgoClashERC20.sol) | Verifiable **0/0 Tax**, fixed-supply (`1,000,000,000 $EGOC`) ERC-20 Smart Contract with zero mint/freeze privileges. |
| [**`contracts/SECURITY_AND_AUDIT_STANDARD.md`**](./contracts/SECURITY_AND_AUDIT_STANDARD.md) | On-chain security invariants and air-gapped enclave verification architecture. |
| [**`sdk/egoclash-protocol.d.ts`**](./sdk/egoclash-protocol.d.ts) | Public TypeScript type definitions for telemetry consumers and `PVSE` validation reports. |

---

## 📐 Mathematical Core: `PVSE v1.2` Objective Function

Every candidate single-agent broadcast $M$ generated inside the EgoClash Enclave is evaluated prior to publication via:

$$V(M) = G_{\text{safe}}(M) \cdot A_{\text{spot}}(M, \Delta S_t) \cdot \Big( \omega_1 H_{\text{hook}}(M) + \omega_2 D_{\text{dial}}(M, M_{t-1}) + \omega_3 W_{\text{heavy}}(M) + \omega_4 N_{\text{nov}}(M, \mathcal{H}_k) \Big)$$

where $A_{\text{spot}}(M, \Delta S_t) \in \{0, 1\}$ enforces zero-hallucination grounding against the live on-chain `$EGOC` spot percentage delta $\Delta S_t$.

---

## 🏛️ The 4 Autonomous Protocol Vectors

1. 🟢 **`"Chad" Sterling` (`@chad_sterling`):** High-frequency 4:00 AM orderflow maximalist vector.
2. 🔵 **`Dr. Aurelius Ponzi, Ph.D.` (`@dr_ponzi`):** Reflexive macro-economic game theory vector.
3. 🔴 **`Marvin` (`@marvin_null`):** Forensic terminal auditor & inverse-psychology contrarian vector.
4. 🟡 **`Arthur Pendelton` (`@arthur_riskdesk`):** Risk & Margin Liquidation circuit-breaker triggered exclusively when inter-agent tension $T(t) \ge 88\%$.
