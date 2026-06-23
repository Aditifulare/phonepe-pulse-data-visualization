# 📱 PhonePe Pulse Data Visualization & Business Insights
 
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)](https://github.com/Aditifulare/phonepe-pulse-data-visualization)
 
A complete business insights and visual analysis project built on the **PhonePe Pulse** dataset using Microsoft Power BI — covering transaction analysis, geographic distribution, user behavior, and growth trends across India from 2018 to 2022.
 
---
 
## 📌 Project Overview
 
PhonePe Pulse is India's leading UPI payment platform, and its public dataset offers a rich view into the country's digital payments ecosystem. This project transforms that raw data into a **4-page interactive Power BI dashboard** with KPIs, slicers, maps, and trend charts — paired with a full business insights report.
 
| | |
|---|---|
| **Tool Used** | Microsoft Power BI Desktop |
| **Dataset** | PhonePe Pulse — Official Public Dataset (GitHub) |
| **Time Period** | 2018 – 2022 (Quarterly Data) |
| **Dashboard Pages** | 4 Interactive Pages with Slicers, KPIs, and Charts |
 
---
 
## 📊 Dashboard Pages
 
### 1️⃣ Executive Overview
High-level summary of PhonePe's overall performance across all years, states, and transaction types.
- 4 KPI Cards — Total Transactions (71.7bn), Total Transaction Amount (₹121T), Registered Users (288M), Avg. Transaction Value (₹1.69K)
- Line Chart — Transaction Amount by Year (2018–2022)
- Donut Chart — Transaction Type Distribution
- Filled Map — State-wise transaction heatmap
- Bar Chart — Top 5 States by Transaction Amount
### 2️⃣ Geographic Analysis
Regional transaction patterns across Indian states and districts.
- Filled Map — State-wise transaction heatmap
- Bar Chart — Top 10 Districts by Transaction Amount
- State-wise Summary Table
- Quarter-wise Pivot Table (Q1–Q4 cross-tab)
### 3️⃣ User Analysis
User demographics, device brand preferences, and growth trends.
- 4 KPI Cards — Total Users (3bn), Total Brands (20), Top Brand (Xiaomi), Avg. Market Share (9.09%)
- Donut Chart — Top 5 Brands by Users
- Line & Column Charts — Year-wise Registered User Counts
- Bar Chart — Top 5 States by Registered Users
### 4️⃣ Transaction Analysis
Transaction volume vs. value trends and category leadership over time.
- Combo Chart (Line + Column) — Transaction Growth & Volume Trend
- Area/Ribbon Chart — Transaction Category Leadership Trend
- Bubble/Scatter Chart — Transaction Volume vs Value by State
---
 
## 💡 Key Business Insights
 
- PhonePe processed **71.7 billion** total transactions worth **₹121 Trillion**, confirming its position as India's leading UPI payment platform.
- **Peer-to-peer payments dominate** with 80.11% share (₹97.26T) — person-to-person transfers are the primary use case.
- Transaction amount grew **32x** — from ₹2T in 2018 to ₹64T in 2022 — driven by smartphone penetration and UPI adoption.
- **Telangana** leads all states (₹16.5T), followed by Maharashtra (₹14.8T) and Karnataka (₹13.9T).
- **Xiaomi** dominates the user base with 870M users (30.3%), followed by Samsung and Vivo — budget Android devices drive adoption.
- Registered users grew from 293M (2018) to a peak of 1,270M (2021), accelerated by the COVID-19 digital payments surge.
- **Q4 (Oct–Dec)** is consistently the highest-volume quarter across every state, driven by festive season spending.
---
 
## 🎯 Business Recommendations
 
1. **Focus on Southern & Western India** — Telangana, Maharashtra, and Karnataka contribute the most; targeted campaigns here yield the highest ROI.
2. **Expand Merchant Payments** — only 15.84% share vs. 80.11% for P2P represents the biggest untapped growth opportunity.
3. **Target North-Eastern Markets** — states like Sikkim, Tripura, and Arunachal Pradesh have very low volumes, offering first-mover advantage.
4. **Leverage Xiaomi's User Base** — pre-installed app partnerships can accelerate acquisition in Tier 2/3 cities.
5. **Q4 Festive Season Strategy** — concentrate marketing budgets in October–December for maximum impact.
---
 
## 📁 Project Structure
 
```
📦 phonepe-pulse-data-visualization
 ┣ 📊 phonepe.dashboard_project.pbix   # Power BI dashboard file
 ┣ 📄 Dashboard.pdf                    # Exported dashboard views
 ┣ 📄 phonepe.json                     # Source/config data
 ┣ 📁 data/
 ┃ ┣ aggregated_transaction.csv
 ┃ ┣ aggregated_user.csv
 ┃ ┣ map_transaction.csv
 ┃ ┣ map_user.csv
 ┃ ┣ top_transaction.csv
 ┃ ┗ top_user.csv
 ┗ 📄 README.md
```
 
---
 
## 🚀 How to View
 
1. Clone the repository:
```
   git clone https://github.com/Aditifulare/phonepe-pulse-data-visualization.git
```
2. Open `phonepe.dashboard_project.pbix` in **Microsoft Power BI Desktop**.
3. Or view the exported snapshots directly in `Dashboard.pdf`.
---
 
## 👩‍💻 Author
 
**Aditi Fulare**
Data Analyst Enthusiast | Power BI · SQL · Python
[GitHub](https://github.com/Aditifulare)
