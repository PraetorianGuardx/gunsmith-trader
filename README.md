# The Apprentice — Gunsmith Trader

A TraderGen add-on. Adds **Nikolai "Kolya" Varga**, a former apprentice of Mechanic who
sells pre-assembled weapons built to every Gunsmith contract specification.

**Version:** 1.0.1

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

Weapon builds follow the publicly documented Gunsmith configurations. Because SPT runs
one patch behind live EFT, individual attachment stats may differ; if a contract is not
accepted, adjust the build.

---

## Changelog

### 1.0.1
Fixed five builds that were rejected in-game. Published parts lists only cover
attachments to buy, not stock parts that have to come off — these five kept
default attachments that broke the contract requirements:

- **Part 5 (M870)** — removed XS SHOTRAIL rail and EOTech XPS3-2 sight
- **Part 18 (AKMN)** — removed NSPU-M night vision scope and eyecup
- **Part 20 (M1A)** — 22 inch barrel swapped for 16 inch with SOCOM 16 muzzle brake
- **Part 21 (M700)** — removed bipod, MDT 12-round magazine swapped for PMAG AC 5-round
- **Part 24 (SR-25)** — removed bipod mount and AN/PEQ-15 tactical device

Prices recalculated from handbook values. The remaining 21 builds were verified
in-game and accepted without changes.

### 1.0.0
Initial release.

## Licence

Copyright (c) 2026 PraetorianGuardx
Released under CC BY-NC-ND 4.0 — see `LICENSE`.

## Credits

- Weapon configurations based on the publicly documented Gunsmith builds
- Built on the TraderGen framework by ShaneeexD
