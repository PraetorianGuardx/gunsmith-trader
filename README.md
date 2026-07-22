# The Apprentice — Gunsmith Trader

A TraderGen add-on. Adds **Nikolai "Kolya" Varga**, a former apprentice of Mechanic who
sells pre-assembled weapons built to every Gunsmith contract specification.

**Version:** 1.0.0

---

## Requirements

| Dependency | Minimum version |
|---|---|
| SPTarkov | 4.0.13 |
| TraderGen (`com.serenity.tradergen`) | 2.0.3 |
| WTT - CommonLib (`com.wtt.commonlib`) | 2.0.20 |

This add-on does **not** bundle those mods — install them separately.

---

## Installation

Drag the `SPT` folder into your SPT installation directory, then start the server.

Do not rename any files or images — the pack references them by name.

---

## Contents

- **26 pre-assembled weapons** covering Gunsmith Part 1–25 (including the Part 21
  M700 / M1911 pair), each built to the quest's specification
- **4-quest storyline** that gates the trader's stock

## Loyalty progression

Each quest awards +0.5 trader standing. Stock unlocks by standing, so progression is
tied to the questline rather than player level alone. The thresholds work for every
EFT edition (starting standing 0.00–0.20).

| Level | Player level | Standing | Turnover | Unlocked by |
|---|---|---|---|---|
| LL1 | 5 | 0.40 | — | The Easy Way |
| LL2 | 12 | 0.90 | 500,000 | Supply Lines |
| LL3 | 18 | 1.40 | 1,500,000 | Quality Control |
| LL4 | 24 | 1.90 | 4,000,000 | Old Debts |

## Trader details

- Stock: 1 of each weapon, restock every 30–60 minutes
- Buys weapons, mods, repair kits and tools — pays slightly better than Mechanic
  (buy price coefficient 43 → 40 by loyalty level; Mechanic is a flat 44)
- Repair enabled
- Not available on the flea market

---

## Notes

Two Gunsmith contracts need a manual adjustment after purchase — these are weapon
states, not parts, so they cannot be stored in a preset:

- **Part 2 (AKS-74U)** — the stock has to be folded
- **Part 14 (HK 416A5)** — the chamber has to be empty, otherwise the weapon is too heavy

Weapon builds follow the publicly documented Gunsmith configurations. Because SPT runs
one patch behind live EFT, individual attachment stats may differ; if a contract is not
accepted, adjust the build at a workbench.

---

## Credits

- Weapon configurations based on the publicly documented Gunsmith builds
- Built on the TraderGen framework by ShaneeexD
