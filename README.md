<div align="center">

# 🥑 AtmoSync — Micro-Climate Arbitrage Analytics

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Food/Avocado.png" width="100" height="100" alt="Avocado" />

### *Real-time IoT Sensor Analytics for In-Transit Spoilage & Rerouting Decisions*

[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Status](https://img.shields.io/badge/Status-Week_2_Complete-00C853?style=for-the-badge&logo=githubactions&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

### 👥 The Analytics Team

| 👤 Team Member | 🎯 Focus Area | 🔗 Profile |
| :--- | :--- | :--- |
| **Mameeth C** | Data Lead & EDA | [@Mameeth-4015](https://github.com/Mameeth-4015) |
| **Aparna C** | Visualizations & Metrics | Analyst |
| **Malavika Nair** | Data Modeling & Spoilage Curves | Analyst |
| **Lucky Aswal** | Quality Validation & Dashboards | Analyst |

</div>

---

## 📌 Project Overview

Traditional supply chain analytics rely on standard transit times and macro-weather forecasts — missing hyper-local **micro-climate shifts** (e.g., a humidity spike inside a single container) that quietly spoil agricultural cargo in transit.

```text
 🚚 [ CONTAINER TRANSIT ] ───► 🌡️ [ THERMAL DRIFT DETECTED ] ───► ⚠️ [ SPOILAGE RISK ]
                                                                        │
 💰 [ CAPTURE RECOVERED VALUE ] ◄─── 🔄 [ REROUTE TO SECONDARY ] ◄──────┘
AtmoSync simulates a live IoT sensor pipeline across 550 refrigerated shipping containers:

📊 Calculates a continuous Real-Time Spoilage Risk Score.

🔀 Identifies Spoilage Arbitrage opportunities — flagging containers to reroute to closer secondary markets before quality falls below saleable thresholds.
📊 Sprint Milestones & Progress
Week 1: Data Foundations & EDA             [████████████████████] 100%
Week 2: Dashboards & Statistical Modeling  [███████████████] 60%
#,Task,Status
1,Built real-time continuous temperature trace & anomaly boundary charts,✅
2,Modeled produce quality degradation curves across transit duration,✅
3,Mapped risk status classifications against automated rerouting workflows,✅
4,Constructed multi-metric correlation heatmaps for environmental drivers,✅
5,Evaluated commodity price differentials between primary & secondary markets,✅
┌──────────────────────────────────────┐  ┌──────────────────────────────────────┐
 │  Chart 1: Temperature Trace Analysis │  │  Chart 3: Quality Loss by Produce    │
 │  📈 Real-time thermal breach tracking│  │  🍓 Strawberries vs 🍅 Tomatoes      │
 └──────────────────────────────────────┘  └──────────────────────────────────────┘
 ┌──────────────────────────────────────┐  ┌──────────────────────────────────────┐
 │  Chart 5: Risk & Rerouting Actions   │  │  Chart 7: Market Price Arbitrage     │
 │  🚦 Normal / Watch / At-Risk / Critical│ │  ⚖️ Target vs Secondary Market Margins│
 └──────────────────────────────────────┘  └──────────────────────────────────────┘
Temperature Drift (chart1_temperature_trace.png): Identifies cooling unit failures leading to thermal breaches during transit.Commodity Sensitivity (chart3_quality_by_commodity.png): Highlights rapid quality loss in highly delicate goods (Strawberries, Blueberries) relative to resilient crops.Micro-Climate Correlation (chart6_correlation_heatmap.png): Confirms temperature deviation (temp_deviation_c) as the single strongest negative predictor of product quality ($r = -0.84$).
🐍 Python 3.11    ──►    🐼 pandas    ──►    📊 matplotlib / seaborn    ──►    📊 Executive Deck
 (Data Generation)        (Cleaning/EDA)              (Visuals)                    (AtmoSync.pptx)
atmosync-analytics/
│
├── 📂 data/
│   ├── 📄 atmosync_dataset.csv             # Raw 50,000-row IoT sensor dataset
│   └── 📄 cleaned_dataset.csv              # Validated & cleaned dataset
│
├── 📂 notebooks/
│   ├── 📓 Dataset Cleaning.ipynb           # Data cleaning & validation notebook
│   └── 📓 week2_dashboard_and_insights.ipynb # Visual dashboards & analytical modeling
│
├── 📂 visuals/
│   ├── 🖼️ chart1_temperature_trace.png
│   ├── 🖼️ chart2_temp_deviation_hist.png
│   ├── 🖼️ chart3_quality_by_commodity.png
│   ├── 🖼️ chart4_quality_vs_transit_scatter.png
│   ├── 🖼️ chart5_risk_and_action_counts.png
│   ├── 🖼️ chart6_correlation_heatmap.png
│   └── 🖼️ chart7_price_comparison.png
│
├── 📊 AtmoSync.pptx                         # Executive presentation deck
└── 📝 README.md
