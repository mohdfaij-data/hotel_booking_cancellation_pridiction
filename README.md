<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0,0D1117,1a1a2e,16213e,0f3460&height=280&section=header&text=HOTEL%20BOOKING%20INTELLIGENCE&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=45&desc=Cancellation%20Prediction%20%26%20Reservation%20Intelligence%20Engine&descSize=16&descAlignY=65&descColor=a0aec0" width="100%"/>

</div>

<div align="center">

[![Power BI Dashboard](https://img.shields.io/badge/LIVE%20DASHBOARD-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=000000)](YOUR_DASHBOARD_LINK)
[![Full Report](https://img.shields.io/badge/FULL%20REPORT-PDF-FF4B4B?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](YOUR_REPORT_LINK)
[![SQL Queries](https://img.shields.io/badge/SQL%20QUERIES-View-00C4CC?style=for-the-badge&logo=postgresql&logoColor=white)](./sql/)
[![Python Notebook](https://img.shields.io/badge/ML%20NOTEBOOK-Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](./python/)

</div>

<br/>

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│    119,400 Reservations  ·  37% Cancellation Rate  ·  $101.83 ADR      │
│    235,000 Guests  ·  5 Dashboards  ·  6 Strategic Insights            │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

</div>

---

## ◈ Project Overview

> **A full-cycle hospitality analytics system** that predicts booking cancellations, uncovers revenue leakage, and delivers strategic intelligence across City & Resort hotel properties — transforming 119K raw reservations into decision-grade business intelligence.

This project spans the complete analytics lifecycle: raw data → SQL transformation → Python ML modeling → Power BI dashboards → executive strategy report. Every layer is designed for real business impact.

---

## ◈ Dashboard Architecture

<div align="center">

| # | Dashboard | Focus Area | Key Visual |
|---|-----------|------------|------------|
| `01` | **Hotel Performance Overview** | Bookings · Cancellations · ADR · Guest Volume | Monthly trend + market treemap |
| `02` | **Cancellation Risk & Loss Analysis** | Segment risk · Lead time · Monthly trends | Cancellation matrix + flow chart |
| `03` | **Pricing Behavior & Revenue Yield** | ADR by hotel · Customer segment · Booking status | Box plots + stream chart |
| `04` | **Guest Behavior & Acquisition** | Stay patterns · Booking channels · Repeat rates | Sankey flow + global map |
| `05` | **Strategic Insights & Recommendations** | 6 findings · 3 action pillars · Decision framework | Insight cards |

</div>

<br/>

> 🔗 **[Open Live Power BI Dashboard](YOUR_DASHBOARD_LINK)** · 📄 **[Download Full PDF Report](YOUR_REPORT_LINK)**

---

## ◈ Core Metrics Snapshot

<div align="center">

| KPI | Value | Signal |
|-----|-------|--------|
| Total Reservations | **119,400** | Across both hotel types |
| Cancellation Rate | **37.0%** | ⚠️ High — primary risk factor |
| Average Daily Rate | **$101.83** | Resort Hotel commands premium |
| Total Guests | **235,000** | Transient = 75.1% dominant segment |
| Avg. Booking Lead Time | **104 days** | Direct impact on cancellation risk |
| Repeat Guest Rate | **3.2%** | Retention gap opportunity |
| Parking Demand | **7,464 requests** | Consistently high across segments |
| Avg. Stay Duration | **3.43 nights** | Resort (4.3) vs City (3.0) |
| Room Upgrade Rate | **12.49%** | Upsell signal |
| Returning Guest Cancellation | **14.5%** | Lower risk in returning cohort |

</div>

---

## ◈ Critical Findings

```
INSIGHT 01 ──────────────────────────────────────────────────────────────────
  Online TA = Highest Volume + Highest Cancellation Rate (36.7%)
  → OTA dependency creates structural revenue risk
  ACTION: Prepaid OTA offers · Stricter cancellation policies · Direct campaigns

INSIGHT 02 ──────────────────────────────────────────────────────────────────
  Peak Demand: July–August (ADR hits $160 in Room Type C)
  → Untapped yield management opportunity in peak months
  ACTION: Dynamic pricing + operational surge readiness

INSIGHT 03 ──────────────────────────────────────────────────────────────────
  Parking Requests Consistently High Across All Segments
  → Unmonetized high-demand amenity
  ACTION: Premium reserved parking · Capacity management system

INSIGHT 04 ──────────────────────────────────────────────────────────────────
  Resort Hotel ADR > City Hotel ADR
  → Stronger premium pricing power in resort segment
  ACTION: Luxury packages · Seasonal premium upsells · Experience bundles

INSIGHT 05 ──────────────────────────────────────────────────────────────────
  Transient Customers = 75.1% of All Bookings
  → Dominant segment with low loyalty investment
  ACTION: Personalized loyalty tiers · Direct booking incentives

INSIGHT 06 ──────────────────────────────────────────────────────────────────
  Groups Segment: 61% Cancellation Rate — Highest Risk Segment
  → Massive revenue leakage from group block cancellations
  ACTION: Deposit requirements · Group contract enforcement · Risk scoring
```

---

## ◈ Cancellation Risk Matrix

<div align="center">

| Segment | Contract | Group | Transient | Transient-Party | **Total** |
|---------|----------|-------|-----------|-----------------|-----------|
| Aviation | — | 0.00% | 21.10% | 35.29% | **21.94%** |
| Complementary | 0.00% | 0.00% | 13.23% | 12.50% | **13.06%** |
| Corporate | 18.18% | 17.24% | 18.29% | 19.72% | **18.73%** |
| Direct | 14.29% | 13.43% | 15.54% | 13.55% | **15.34%** |
| **Groups** | 95.92% | 0.00% | 95.69% | 31.30% | **⚠️ 61.06%** |
| Offline TA/TO | 9.19% | 11.85% | 42.63% | 26.15% | **34.32%** |
| **Online TA** | 25.84% | 6.15% | 38.80% | 12.52% | **⚠️ 36.72%** |
| **TOTAL** | 30.96% | 10.23% | 40.75% | 25.43% | **37.04%** |

</div>

---

## ◈ Strategic Action Pillars

<div align="center">

```
┌──────────────────────────┐  ┌──────────────────────────┐  ┌──────────────────────────┐
│                          │  │                          │  │                          │
│   01. REDUCE             │  │   02. GROW               │  │   03. RETAIN             │
│   CANCELLATION LOSSES    │  │   REVENUE & ADR          │  │   GUESTS DIRECTLY        │
│                          │  │                          │  │                          │
│  · Predictive risk flags │  │  · Dynamic peak pricing  │  │  · Loyalty tier system   │
│  · OTA deposit mandates  │  │  · Resort luxury bundles │  │  · Personalized offers   │
│  · Lead time policies    │  │  · Yield management      │  │  · Direct booking UX     │
│  · Group contract rules  │  │  · Upsell automation     │  │  · Member-only rates     │
│                          │  │                          │  │                          │
└──────────────────────────┘  └──────────────────────────┘  └──────────────────────────┘
```

</div>

---

## ◈ Technology Stack

<div align="center">

### Data & Querying
![SQL](https://img.shields.io/badge/SQL-Advanced-336791?style=flat-square&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-M%20Language-F2C811?style=flat-square&logo=powerbi&logoColor=000)
![DAX](https://img.shields.io/badge/DAX-Measures%20%26%20KPIs-F2C811?style=flat-square&logo=powerbi&logoColor=000)

### Visualization & BI
![Power BI](https://img.shields.io/badge/Power%20BI-5%20Dashboards-F2C811?style=flat-square&logo=powerbi&logoColor=000000)
![Power BI Service](https://img.shields.io/badge/Power%20BI%20Service-Live%20Publish-F2C811?style=flat-square&logo=powerbi&logoColor=000)

### Analytics & ML
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-EDA-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML%20Model-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)

### Delivery & Reporting
![PDF](https://img.shields.io/badge/Full%20Report-PDF-FF4B4B?style=flat-square&logo=adobeacrobatreader&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white)

</div>

---

## ◈ Repository Structure

```
📦 hotel-booking-intelligence/
│
├── 📂 data/
│   ├── raw/                    → Original hotel booking dataset
│   └── cleaned/                → Processed, feature-engineered dataset
│
├── 📂 sql/
│   ├── 01_cancellation_analysis.sql
│   ├── 02_adr_by_segment.sql
│   ├── 03_monthly_trends.sql
│   ├── 04_guest_behavior.sql
│   └── 05_risk_scoring_queries.sql
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
│   ├── guest_behavior_acquisition.pbix
│   └── strategic_insights.pbix
│
├── 📂 report/
│   ├── hotel_intelligence_full_report.pdf
│   └── executive_summary.pdf
│
└── 📜 README.md
```

---

## ◈ ML Model — Cancellation Predictor

```python
# Cancellation Risk Classification
# Target: booking_status (Canceled / Confirmed)
# Features: lead_time, market_segment, adr, hotel_type,
#           deposit_type, customer_type, booking_changes,
#           previous_cancellations, total_of_special_requests

Model         : Logistic Regression + Random Forest Ensemble
Predicted Risk: Low (60.3%) · Medium (28.2%) · High (11.5%)
Key Driver    : lead_time × market_segment interaction
Use Case      : Flag high-risk bookings at reservation time
```

---

## ◈ Predicted Risk Distribution

<div align="center">

```
  Low Risk    ████████████████████████████████████████  60.3%  (72,000 bookings)
  Medium Risk ████████████████████                      28.2%  (33,600 bookings)
  High Risk   ██████                                    11.5%  (13,700 bookings)
```

</div>

---

<div align="center">

---

**Built for decision-grade analytics — not just dashboards.**

*If this project helped you, consider giving it a ⭐*

[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN)
[![Portfolio](https://img.shields.io/badge/View-Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](YOUR_PORTFOLIO)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0,0D1117,1a1a2e,16213e,0f3460&height=120&section=footer&animation=fadeIn" width="100%"/>
