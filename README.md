# US LTL Freight Class (2026 13-Tier PCF) & Carrier W&I Open Reference Dataset

Clean, machine-readable MIT-licensed CSV & JSON datasets for US LTL logistics developers, 3PLs, WMS/TMS builders, and small warehouse shippers:

- **2026 13-Tier Density Scale** (`data/2026-13-tier-pcf-scale.json` / `.csv`) — Docket 2025-1 volumetric PCF bands from Sub 1 (<1 PCF, Class 400) to Sub 13 (50+ PCF, Class 50).
- **5-Carrier Published W&I Reweigh Tolerances & Dispute Windows** (`data/2026-carrier-wi-tolerances.json` / `.csv`) — XPO, FedEx Freight, Estes, Saia, and Old Dominion (ODFL) base rules-tariff references (`Last Verified: 2026-11-26`).
- **Pre-Pickup Dock & BOL Checklist** (`docs/bol-pre-pickup-checklist.md`) — Practical steps to prevent 96" "Do Not Stack" reclasses and W&I adjustments.

## Interactive Web Tools (Free, Zero-Login)

Maintained by **[FreightClassKit](https://freightclasskit.com/)**:
- [2026 Freight Class Calculator & 96" Do Not Stack Simulator](https://freightclasskit.com/)
- [2026 13-Tier Freight Class Chart](https://freightclasskit.com/freight-class-chart)
- [Free Printable Straight & VICS BOL PDF Generator (Code 128)](https://freightclasskit.com/bol-generator)
- [Carrier W&I Reweigh Dispute Workbench](https://freightclasskit.com/reweigh-dispute)
- [Carrier Reweigh Thresholds & Tariff Links](https://freightclasskit.com/guides/carrier-reweigh-thresholds)

## 2026 13-Tier Density Scale Summary

| Sub | Density Band (PCF) | Freight Class |
|---:|---|---|
| 1 | `< 1` | 400 |
| 2 | `1 to < 2` | 300 |
| 3 | `2 to < 4` | 250 |
| 4 | `4 to < 6` | 175 |
| 5 | `6 to < 8` | 125 |
| 6 | `8 to < 10` | 100 |
| 7 | `10 to < 12` | 92.5 |
| 8 | `12 to < 15` | 85 |
| 9 | `15 to < 22.5` | 70 |
| 10 | `22.5 to < 30` | 65 |
| 11 | `30 to < 35` | 60 |
| 12 | `35 to < 50` | 55 |
| 13 | `50+` | 50 |

## Disclaimer

Density estimates follow public volumetric math (`PCF = Gross Weight lbs / (L × W × H in / 1728)`). FreightClassKit is independent and not affiliated with NMFTA. Always confirm official 6-digit NMFC item numbers with your carrier or NMFTA ClassIT+.
