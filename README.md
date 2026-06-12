
# ATM Transaction & Revenue Dashboard — Power BI

![ATM Transation Dashbaord Project _page-0001](https://github.com/user-attachments/assets/f39a0697-c9db-47ed-b132-b731426bd8d4)

Multi-page Power BI dashboard providing a comprehensive view of ATM network performance across Indian states — covering revenue generation, gross profit, transaction volumes, operational uptime, and cost analysis for 2,374+ ATMs.

**Business question:** Which ATMs and regions are driving profitability, which are underperforming, and what operational levers most impact gross margin?

---

## Dashboard pages

| Page | Purpose |
|---|---|
| **Home** | Navigation hub and project overview |
| **Overview** | Network-wide KPIs: revenue, transactions, uptime, gross profit |
| **Details** | ATM-level performance by transaction range and margin band |

---

## Key metrics tracked

| Metric | Value |
|---|---|
| Total cost analysed | 296 million |
| Average monthly revenue per ATM | 52.13K |
| Gross profit margin | 59.60% |
| Average ATM uptime | 91.9% |
| Average monthly transactions per ATM | 178.89 |
| ATMs with margin > 30% | 2,374 |
| ATMs with negative margin | 549 |

---

## Dashboard previews

**Overview page — network KPIs and revenue trends**
![Overview](https://github.com/user-attachments/assets/a62b4dcd-b863-4043-b0b5-c5bc8304b1ff)

**Details page — transaction ranges and margin analysis**
![Details](https://github.com/user-attachments/assets/b46851c4-1d06-45ab-b04f-c46c870b4153)

---

## Key findings

**By transaction volume:**
- ATMs processing 50K+ transactions deliver 93.3% uptime and 64.11% gross profit — the highest-performing tier
- ATMs below 10K transactions show 82.6% uptime and inflated gross profit % due to low cost base — but represent operational risk

**By geography (top states):**
- Punjab leads in average transactions per ATM: 67.14/month
- Ladakh achieves the highest uptime (93.8%) and 75.45% gross profit
- Manipur outlier: 111.85% gross profit — flagged for further investigation

**By margin band:**
- 549 ATMs operate at negative margin — concentrated in specific states and transaction ranges
- Targeted intervention on these units represents the highest-ROI improvement opportunity

---

## Tools used

- **Power BI** — data modelling, DAX measures, multi-page dashboard design, KPI cards, trend charts
- **Excel** — data cleaning and preparation
- **Data source** — [Here](https://drive.google.com/drive/folders/1s-sRpKMHHD4TMj0aHuCxiGheaVYbn-3v))

---

## DAX measures built

- Monthly Revenue (rolling calculation)
- Gross Profit % by ATM and region
- Average Uptime % with threshold flagging
- Transaction volume bands (dynamic categorisation)
- MoM revenue variance

---

## Design decisions

- **Colour palette:** Sky blue (#A0D1FF) · Blue (#0D6ABF) · Red (#D64550) — chosen for clear positive/negative signal contrast on financial KPIs
- **Navigation structure:** Home → Overview → Details mirrors how a stakeholder would investigate — from headline numbers down to root cause
- **Margin band approach:** Categorising by margin % rather than absolute revenue makes the analysis actionable for ATM network managers regardless of region size

---

## Recommendations

1. **Prioritise uptime improvement** in the sub-10K transaction tier — a 5% uptime increase in this band would meaningfully shift them into profitability
2. **Investigate the 549 negative-margin ATMs** — determine whether these are structural (location, cost base) or operational (downtime, low activation)
3. **Replicate Ladakh operating model** — highest combined uptime and gross profit; document and apply best practices network-wide
4. **Set Punjab as transaction benchmark** — 67.14 avg transactions/ATM is the network high; use as the KPI target for underperforming states

---

## Files

| File | Description |
|---|---|
| `README.md` | This file |
| `screenshots/` | Dashboard page screenshots |

