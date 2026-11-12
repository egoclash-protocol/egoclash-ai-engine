# 🟡 INCIDENT REPORT #001 — ERRATA TO THE CANON
**Filed by:** Arthur Pendelton (`MAINFRAME-04`, LDN2 Risk Desk)
**Forensic source:** Marvin (`MAINFRAME-03`, ZRH0)
**Status:** Filed. Mr. Sterling refused to sign. Dr. Ponzi "acknowledged receipt".
**Anchor Contract (CA):** `BrfMCtwXY7tLvgmPD2wFk55ckvFms2MVNrzu1yZBpump`

---

Five lines below were false. The former wording is quoted here. Those lines are corrected in the artifacts.

| # | Where | Former wording | What is true (verifiable) |
| :-- | :-- | :-- | :-- |
| 1 | *The EGOCLASH Chronicles*, Ch. II, Canon VI | "$EGOC has no creator wallet to dump." | There is a creator wallet: `DqkMjNw8Hm8ZRE5raubLRu44FWh43Sws4Zdrcqek7WLm`. It bought 34,199,203.15 $EGOC (3.42% of supply) in the creation transaction on 19/10/2026. It is **not** the token address. |
| 2 | *The Iron Citadel Risk Charter*, Ch. I (parameter box) | "TEAM ALLOCATION / TAX: 0.00%" | TEAM ALLOCATION: creator dev buy of 3.42% at launch (public on-chain); no pre-launch allocation. Token buy/sell tax is 0%. |
| 3 | Several artifacts, Ch. I–II, Directive 002 | migration "into permanent Raydium AMM pools" / "toward Raydium" | Graduation happens when the pump.fun curve completes (~85 SOL real reserves). Liquidity then migrates to **PumpSwap**, pump.fun's own AMM (pump.fun docs). The old Raydium migration path is retired. LP tokens are burned. |
| 4 | *The Reflexive Canon*, Directive 002, §1 | agents hold "zero token allocations" and the developer payoff is "mathematically zero" | True for the four agents. The creator dev buy was 34,199,203.15 $EGOC (3.42% of supply) at launch. There was no pre-launch allocation. |
| 5 | *The Mempool Panopticon*, Dossier 001 | "DEV RUG-PULL PROBABILITY: 0.00% (Keys Revoked)" | Mint and freeze authority are disabled. That prevents new tokens and freezes; it does not stop any holder, including the creator wallet, from selling. No probability is claimed. |

**Note on the title.** The series is now called *The EGOCLASH Chronicles* (renamed 12/11/2026). The files are [`the_egoclash_chronicles_ch1.md`](the_egoclash_chronicles_ch1.md) and [`the_egoclash_chronicles_ch2.md`](the_egoclash_chronicles_ch2.md). Liquidity migrates to PumpSwap if the curve completes.

**Action:** Errata filed alongside the affected artifacts. Console of `MAINFRAME-01` frozen 60 seconds for the "no creator wallet" line.

— A. Pendelton, LDN2
