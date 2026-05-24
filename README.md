<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:434343&height=250&section=header&text=SmartHotel%20Analytics&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Booking%20Cancellation%20Prediction%20%26%20Reservation%20Intelligence&descAlignY=58&descSize=18"/>
</p>

<div align="center">

<a href="YOUR_DASHBOARD_LINK"><img src="https://img.shields.io/badge/⬡%20LIVE%20DASHBOARD-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=000"/></a>&nbsp;
<a href="Hotel Booking Cancellation Prediction Report.pdf"><img src="https://img.shields.io/badge/↓%20FULL%20REPORT-PDF-FF4B4B?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>&nbsp;
<a href="./sql/"><img src="https://img.shields.io/badge/⌗%20SQL%20QUERIES-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/></a>&nbsp;
<a href="EDA Report.pdf"><img src="https://img.shields.io/badge/◈%20ML%20NOTEBOOK-Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/></a>

<br/><br/>

![Stars](https://img.shields.io/github/stars/mohdfaij-data/hotel_booking_cancellation_pridiction?style=flat-square&color=gold&label=⭐%20Stars)
![Last Commit](https://img.shields.io/github/last-commit/mohdfaij-data/hotel_booking_cancellation_pridiction?style=flat-square&color=2dd4bf&label=Last%20Commit)
![Repo Size](https://img.shields.io/github/repo-size/mohdfaij-data/hotel_booking_cancellation_pridiction?style=flat-square&color=a78bfa&label=Repo%20Size)

</div>

<br/>

---

<div align="center">

## ` 119,400 Reservations · 37.0% Cancellation Rate · $101.83 ADR · 235K Guests `

</div>

---

<br/>

## ◈ What This Project Does

> **Transforms raw hotel reservation data into a full decision-grade intelligence system** — covering cancellation prediction, revenue yield analysis, guest acquisition behavior, and strategic recommendations — across City & Resort hotel properties.

Built across the **complete analytics lifecycle:**

```
Raw CSV Data  →  SQL Cleaning & Segmentation  →  Python EDA & ML Modeling
     →  Power BI (5 Dashboards)  →  PDF Executive Report  →  GitHub
```

<br/>

---

## ◈ Dashboard 01 — Hotel Performance Overview

> Bookings · Cancellations · ADR · Guest Volume · Monthly Trends · Market Treemap

<img src="screenshots/hotel_overview.png" width="100%"/>

<div align="center">

| Metric | Value |
|:--|:--|
| Total Reservations | **119,400** |
| Cancellation Rate | **37.0%** |
| City Hotel Volume | **79K bookings** |
| Resort Hotel Volume | **40K bookings** |
| Peak Month | **July–August** |

</div>

<br/>

---

## ◈ Dashboard 02 — Cancellation Risk & Loss Analysis

> Segment-Level Risk · Lead Time Impact · Monthly Trends · Predicted Risk Distribution

<img src="screenshots/cancellation.png" width="100%"/>

<div align="center">

| Metric | Value |
|:--|:--|
| Cancelled Reservations | **44,200** |
| Confirmed Reservations | **75,200** |
| Avg. Booking Lead Time | **104 days** |
| Returning Guest Cancellation | **14.5%** |
| Highest Risk Segment | **Groups — 61.06% ⚠️** |

</div>

<br/>

---

## ◈ Dashboard 03 — Pricing Behavior & Revenue Yield

> ADR by Hotel & Booking Status · Customer Value vs Cancellation · Monthly ADR by Type

<img src="screenshots/ADR.png" width="100%"/>

<div align="center">

| Customer Type | Avg ADR | Cancellation Rate |
|:--|:--|:--|
| Transient | **$107.0** | 40.7% ⚠️ |
| Contract | **$87.5** | 31.0% |
| Transient-Party | **$86.1** | 25.4% |
| Group | **$83.5** | 10.2% ✅ |

</div>

<br/>

---

## ◈ Dashboard 04 — Guest Behavior & Acquisition Insights

> Stay Patterns · Booking Channels · Repeat Rates · Sankey Acquisition Flow · Global Map

<img src="screenshots/customers.png" width="100%"/>

<div align="center">

| Metric | Value |
|:--|:--|
| Returning Guests | **3.19** |
| Average Stay Duration | **3.43 nights** |
| Parking Requests | **7,464** |
| Repeat Guest Rate | **3.19%** |
| Room Upgrade Rate | **12.49%** |
| Transient Share | **75.1% of all bookings** |

</div>

<br/>

---

## ◈ Dashboard 05 — Strategic Insights & Recommendations

> 6 Data-Driven Findings · 3 Action Pillars · Filterable by City & Resort Hotel

<img src="screenshots/strategies.png" width="100%"/>

<br/>

---

## ◈ Cancellation Risk Matrix

<div align="center">

| Segment | Contract | Group | Transient | Trans-Party | **Total** |
|:--|:--:|:--:|:--:|:--:|:--:|
| Aviation | — | 0.00% ✅ | 21.10% | 35.29% | 21.94% |
| Complementary | 0.00% ✅ | 0.00% ✅ | 13.23% | 12.50% | 13.06% ✅ |
| Corporate | 18.18% | 17.24% | 18.29% | 19.72% | 18.73% |
| Direct | 14.29% | 13.43% | 15.54% | 13.55% | 15.34% ✅ |
| **Groups** | **95.92% ⚠️** | 0.00% | **95.69% ⚠️** | 31.30% | **61.06% 🔴** |
| Offline TA/TO | 9.19% | 11.85% | 42.63% 🟡 | 26.15% | 34.32% 🟡 |
| **Online TA** | 25.84% | 6.15% | 38.80% 🟡 | 12.52% | **36.72% 🟡** |
| **TOTAL** | **30.96%** | **10.23%** | **40.75%** | **25.43%** | **37.04%** |

</div>

<br/>

---

## ◈ ML Model — Cancellation Predictor

```python
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  MODEL     Logistic Regression + Random Forest Ensemble
  TARGET    booking_status  →  Canceled / Confirmed
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  FEATURES  lead_time           market_segment      adr
            hotel_type          deposit_type        customer_type
            previous_cancels    booking_changes     special_requests
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  KEY DRIVER  →  lead_time  ×  market_segment  interaction
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  PREDICTED RISK DISTRIBUTION

  🟢 Low Risk     ████████████████████████████████  60.3%  →  72,000 bookings
  🟡 Medium Risk  ████████████████                  28.2%  →  33,600 bookings
  🔴 High Risk    ██████                            11.5%  →  13,700 bookings
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

---

## ◈ Strategic Action Pillars

```
┌─────────────────────────────┐ ┌─────────────────────────────┐ ┌─────────────────────────────┐
│  01 · REDUCE CANCELLATIONS  │ │  02 · GROW REVENUE & ADR    │ │  03 · RETAIN GUESTS         │
├─────────────────────────────┤ ├─────────────────────────────┤ ├─────────────────────────────┤
│ → Predictive risk flags     │ │ → Dynamic peak pricing      │ │ → Personalized loyalty tiers│
│ → OTA deposit mandates      │ │ → Resort luxury bundles     │ │ → Direct booking incentives │
│ → Lead time policies        │ │ → Yield management system   │ │ → Member-exclusive rates    │
│ → Group contract rules      │ │ → Upsell automation         │ │ → Mobile UX optimization    │
│ → Advance payment triggers  │ │ → Parking monetization      │ │ → Exclusive member offers   │
└─────────────────────────────┘ └─────────────────────────────┘ └─────────────────────────────┘
```

<br/>

---

## ◈ Technology Stack

<div align="center">

| Layer | Tools |
|:--|:--|
| **Data & Querying** | ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat-square&logo=powerbi&logoColor=000) ![Power Query](https://img.shields.io/badge/Power%20Query%20M-F2C811?style=flat-square&logo=powerbi&logoColor=000) |
| **Visualization & BI** | ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=000) ![Power BI Service](https://img.shields.io/badge/Power%20BI%20Service-F2C811?style=flat-square&logo=powerbi&logoColor=000) |
| **Analytics & ML** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |
| **Delivery** | ![PDF](https://img.shields.io/badge/PDF%20Report-FF4B4B?style=flat-square&logo=adobeacrobatreader&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

</div>

<br/>

---

## ◈ Repository Structure

```
📦 hotel_booking_cancellation_pridiction/
│
├── 📂 data/
│   ├── raw/                          → original hotel booking dataset
│   └── cleaned/                      → processed & feature-engineered dataset
│
├── 📂 sql/
│   ├── 01_cancellation_analysis.sql
│   ├── 02_adr_by_segment.sql
│   ├── 03_monthly_trends.sql
│   └── 04_guest_behavior.sql
│
├── 📂 python/
│   ├── 01_eda_exploration.ipynb
│   ├── 02_feature_engineering.ipynb
│   └── 03_cancellation_ml_model.ipynb
│
├── 📂 powerbi/
│   ├── hotel_performance_overview.pbix
│   ├── cancellation_risk_analysis.pbix
│   ├── pricing_revenue_yield.pbix
│   └── guest_behavior_acquisition.pbix
│
├── 📂 screenshots/
│   ├── hotel_overview.png
│   ├── cancellation.png
│   ├── ADR.png
│   ├── customers.png
│   └── strategies.png
│
├── 📂 report/
│   ├── hotel_intelligence_full_report.pdf
│   └── executive_summary.pdf
│
└── 📜 README.md
```

---

<div align="center">

<br/>

**Built for decision-grade analytics — not just dashboards.**

<br/>

<a href="www.linkedin.com/in/mohdfaij-data"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>&nbsp;
<a href="https://mohdfaij-data.github.io"><img src="https://img.shields.io/badge/View%20Portfolio-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

*If this project helped you, drop a ⭐ — it keeps the work going.*

<br/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=120&section=footer&animation=fadeIn" width="100%"/>
