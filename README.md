# 🚲 Toman Bike Share - Executive Analytics & Business Strategy

An end-to-end data analytics and dashboard development project evaluating operational performance, rider demographics, peak hourly demand, and seasonal revenue trends for Toman Bike Share.

---

## 📌 Executive Summary

Toman Bike Share experienced rapid business expansion over the analyzed period, achieving **$15.19M in total revenue** with an extraordinary **+106.20% Year-over-Year (YoY) growth rate**. 

This analytics suite transitions raw operational datasets into actionable, C-suite business recommendations through an interactive two-page Power BI executive dashboard.

---

## 📊 Dashboard Overview

The Power BI report consists of two structured analytical views:

1. **Executive Operational Dashboard:** Focuses on core KPIs, monthly performance tracking, demographic breakdowns, and interactive matrix filtering.
2. **Executive Insights & Strategy (2x2 Grid):** Pairs key analytical visuals directly with strategic business recommendations.

---

## 💡 Key Business Findings & Strategic Recommendations

### 1. Financial Growth & Pricing Strategy
* **Finding:** Total Revenue hit **$15.19M** (+106.20% YoY growth), proving high demand elasticity and platform adoption.
* **Recommendation:** Implement a conservative **10%–15% price increase** for the upcoming operational year to optimize profit margins without triggering customer churn.

### 2. Rider Segmentation & Pass Customization
* **Finding:** Registered members account for **81.17% ($2.7M)** of total ridership, providing a highly predictable daily commuter revenue baseline. Casual riders comprise **18.83% ($0.6M)**.
* **Recommendation:** Protect base member loyalty by maintaining annual subscription rates, while introducing dynamic pricing and premium weekend day-passes for casual riders.

### 3. Commuter Rush-Hour Rebalancing & Operations
* **Finding:** System demand exhibits two distinct daily peaks aligned with work hours: a morning rush at **8:00 AM ($1.21M)** and an evening surge peaking at **5:00 PM ($1.55M)**.
* **Recommendation:** Perform targeted fleet rebalancing prior to 8:00 AM and 5:00 PM. Schedule all routine servicing, battery swaps, and heavy maintenance during the off-peak overnight window (**1:00 AM – 5:00 AM**).

### 4. Seasonal Performance & Fleet Availability
* **Finding:** Revenue peaks during **Fall ($4.9M)** and **Summer ($4.2M)**, while **Spring ($2.2M)** experiences the lowest annual demand.
* **Recommendation:** Use Spring as the primary overhaul window to conduct heavy repairs and fleet upgrades, ensuring 100% capacity is deployed during peak Summer and Fall months.

---

## 🛠️ Tools & Data Pipeline

* **Data Querying & Transformation:** SQL / Power Query
* **Data Modeling & Measures:** DAX (Data Analysis Expressions)
* **Visualization & Reporting:** Power BI Desktop
* **Repository Architecture:** Git & GitHub

---

## 📸 Dashboard Preview

| Main Executive Dashboard | Strategic Insights (2x2 Grid) |
| :---: | :---: |
| *![Main Dashboard](Visuals/dashboard_p1.png)* | *![Executive Insights](Visuals/dashboard_p2.png)* |

---

## 📁 Repository Structure

```text
├── Dashboard/
│   └── Toman_Bike_Share_Analysis.pbix
├── Datasets/
│   └── bike_share_data.csv
├── Documentation/
│   └── Executive_Report.pdf
├── Visuals/
│   ├── dashboard_p1.png
│   └── dashboard_p2.png
└── README.md
