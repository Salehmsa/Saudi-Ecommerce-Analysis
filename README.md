# NoorTrade — Executive Sales Performance Analysis 2022–2024

> **End-to-End Data Analytics** | Python · Pandas · NumPy · Matplotlib · Seaborn

---

## Business Question

*"How did NoorTrade perform across 2022–2024, and what are the strategic opportunities for 2025?"*

A full 3-year performance audit for a Saudi e-commerce and retail company spanning **8 cities**, **5 product categories**, and **8,000+ transactions**.

---

## Key Findings

| Finding | Detail |
|---|---|
| Revenue Growth | ~22% YoY — sustained across all 3 years |
| Channel Shift | Online + App outpace Store by 3x |
| Geographic Concentration | Riyadh + Jeddah = 65% of revenue |
| Seasonal Peaks | Ramadan +40% · White Friday +120% |
| Return Rate | 5% — operational gaps in Wrong Item & Damaged in Transit |

---

## Project Structure

```
NoorTrade-Portfolio/
├── NoorTrade_Analysis.ipynb   # Main analysis (27 KPIs, 12+ visualizations)
├── data/
│   ├── noortrade_data.xlsx    # Dataset: Orders, Customers, Products, Returns
│   └── noortrade_kpi_summary.csv
└── README.md
```

---

## Analysis Sections

| Section | Content |
|---|---|
| Data Loading | Multi-sheet Excel ingestion |
| Quality Audit | Missing values, duplicates, type validation |
| Cleaning | Whitespace, casing, deduplication, imputation |
| Revenue KPIs | Total, Profit, Margin, AOV, YoY Growth |
| Channel KPIs | Online / App / Store mix evolution |
| Geographic KPIs | City ranking, growth rates, concentration risk |
| Product KPIs | Category revenue, margin analysis, top products |
| Customer KPIs | CLV, repeat rate, New vs Returning, age segments |
| Seasonality | Monthly patterns, Ramadan effect, day-of-week |
| Returns | Rate, reason breakdown, category analysis |
| Executive Dashboard | Single-pane KPI summary |
| Strategic Insights | 7 actionable recommendations |

---

## How to Run

```bash
git clone https://github.com/Salehmsa/NoorTrade-Sales-Analysis.git
cd NoorTrade-Sales-Analysis
pip install pandas numpy matplotlib seaborn openpyxl
jupyter notebook NoorTrade_Analysis.ipynb
```

---

## Tech Stack

`pandas` · `numpy` · `matplotlib` · `seaborn` · `openpyxl`

---

## Strategic Recommendations

1. Double down on the channels and cities driving 22% YoY growth
2. Accelerate App investment — highest AOV channel
3. Expand aggressively in Khobar & Abha — fastest growing, lower competition
4. Build a 90-day Ramadan calendar and post-Eid retention campaign
5. Launch a loyalty program targeting one-time buyers
6. Bundle high-margin categories with high-volume low-margin products
7. Fix operational return causes — Wrong Item + Damaged = 35% of returns

---

## Author

**Saleh Mahbub** — Junior Data Scientist | IBM-certified
- GitHub: [github.com/Salehmsa](https://github.com/Salehmsa)
- Email: salehmahbub8@gmail.com
- Location: Riyadh, Saudi Arabia
