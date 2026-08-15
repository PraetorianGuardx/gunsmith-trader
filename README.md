# The Apprentice — Gunsmith Trader

A TraderGen add-on. Adds **Nikolai "Kolya" Varga**, a former apprentice of Mechanic who
sells pre-assembled weapons built to every Gunsmith contract specification.

**Version:** 1.0.5

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

- **32 pre-assembled weapons** covering Gunsmith Part 1–25 (including the Part 21
  M700 / M1911 pair) plus Gunsmith – Special Order, Gunsmith – Old Friend's Request
  (T-5000M, PP-19-01 and Glock 17), Breathing Room and Hell on Earth – Part 1,
  each built to the quest's specification
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

### 1.0.5
Seven weapons carried attachment combinations that EFT refuses to assemble, so the
weapon reaching the player was not the one the file described. Part 6, 11 and 22 only
needed a redundant part dropped and are otherwise unchanged. Part 10, 17 and 18 needed
a dust cover or mount swapped; Part 18 gains ergonomics in the process. Part 15 loses
its skeleton stock, which conflicts with the buffer-tube pistol grip - recoil rises
from 150 to 207 against a limit of 220.

Two of these conflicts predate 1.0.4.

### 1.0.4
Nine builds no longer met their contract and were rebuilt: Part 2, 10, 11, 12, 13,
17, 20, 22 and 25. Most sat just under the ergonomics requirement; Part 11, 12 and 20
failed on recoil sum by a few points. Each rebuild now clears its thresholds with
margin rather than sitting on them, so a stat change in a future SPT release is less
likely to break them again.

Six new weapons for the contracts added to EFT since this mod was first written:
Gunsmith – Special Order (M4A1), Gunsmith – Old Friend's Request (ORSIS T-5000M,
PP-19-01 Vityaz and Glock 17), Breathing Room (IWI UZI) and Hell on Earth – Part 1
(MP-43-1C). Loyalty follows the existing scheme, by position in the quest chain.

### 1.0.3
Supply Lines was pinned to Customs even though none of its objectives happen there —
it hands over tools and nothing else. It is now location-independent.

New artwork for all four quests, and The Easy Way no longer borrows the generic
quest icon.

### 1.0.2
Barter-only attachments are now priced at what they actually cost to acquire.
Handbook values only rate the item itself, not the trade goods needed to obtain
it — for parts that no trader sells for money, the cheapest barter is now used
as the material value instead.

Six weapons changed. The largest is Part 22, where the Trijicon REAP-IR costs
roughly twice its handbook value in trade. Part 18 became cheaper, as the
Rotor 43 suppressor trades below its listed price.

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
