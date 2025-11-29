# 🌐 AtliQ Business Insights 360

A complete 360° Business Intelligence solution built using Power BI, SQL, and Excel, designed to help decision-makers understand revenue, profitability, customer behavior, market performance, and supply chain risks — all in one interactive dashboard.

This project showcases my ability to work with real-world datasets, build a clean data model, create advanced DAX calculations, and design insightful UI/UX dashboards tailored for executives, finance teams, marketing teams, and sales leaders.

# 🚀 Project Summary

AtliQ Business Insights 360 brings together multiple business domains into one unified reporting system:
- 📊 Finance Overview → P&L, Gross Margin, Net Sales, Cost Structure
- 🛒 Sales View → Customer Performance, Unit Economics, GM% Trends
- 📣 Marketing View → Market & Segment Profitability, Regional Trends
- 📦 Supply Chain View → Forecast Accuracy, Net Error, Operational Risk
- 🧭 Executive Dashboard → Top insights across all dimensions of the business
The dashboard enables clear and fast decision-making across teams.

# 🧱 Data Model & Tech Stack

## 🏗 Tech Stack
- Power BI Desktop – Data modeling, DAX, Visuals
- SQL (MySQL) – Fact & Dimension tables
- Power Query – Cleaning & transformation
- Excel – Master data sheets
- DAX – KPIs, Time Intelligence, Benchmarks

## 🗂 Data Model

A professionally built Star Schema with:
- Fact Tables:
fact_sales_monthly, fact_forecast_monthly,
manufacturing_cost, freight_cost,
pre_invoice_deductions, post_invoice_deductions,
gross_price
- Dimension Tables:
dim_customer, dim_market, dim_product,
dim_date, dim_segment, dim_category, etc.
Below is the complete ERD showing the star-schema model used to build this BI project:
![Entity-Relationship Diagram](https://github.com/AlishaMahanty/AtliQ_Business_Insights_360/blob/main/Images/ER_Diagram.png)

# 📸 Live Dashboard

👉 Click the image below to view the full dashboard.
[![Home](https://github.com/AlishaMahanty/AtliQ_Business_Insights_360/blob/main/Images/Home.png)](https://app.powerbi.com/view?r=eyJrIjoiZjZhYWYwZmItYTkzZi00ZjVmLTkwOTAtMjIxNjU2YmZkOTdjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=e43419a2e56c48f99701)

# 📊 Key Insights From the Dashboard

## 1️⃣ Finance View
Deep dive into performance:
- Gross Sales: $535.95M
- Net Sales: $267.98M
- Total COGS: $168.56M
- Operational Expenses: -$101.71M
- Net Profit: -$2.29M
Reason for negative NP%:
High operational costs & invoice deductions.
Sales Trend:
Holiday peaks (Nov–Dec) and a dip in early 2020.

## 2️⃣ Sales View
- Amazon is the highest revenue contributor
- AtliQ Exclusive has the best GM% among major customers
- Some customers (Leader, Sage) have low margins & low sales
- Unit Economics reveals a 62.9% COGS burden, impacting profitability

## 3️⃣ Marketing View
- Canada, Sweden, Netherlands → Healthy NP% markets
- India, USA, Italy → Loss-making despite high revenue
- Clear segmentation of GM% vs NP% for market-level strategy

## 4️⃣ Supply Chain View
- Forecast Accuracy: 73%
- Absolute Error: 5.7M
- Customers facing Out-of-Stock (OOS) risk: Amazon, BestBuy, Circuit City
- Customers with Excess Inventory (EI) risk: Chip7, AtliQ Exclusive, Costco
- This view enables inventory optimization & demand planning.

## 5️⃣ Executive Summary (Top-Level View)
- Net Sales: $267.98M (Above benchmark)
- Gross Margin %: 37.10% (Below benchmark)
- Net Profit %: -0.85% (Operational pressures)
- Forecast Accuracy: 73% (Dropped from LY)
Regionally:
- Strong performers: ROA, SE, ANZ
- Underperformers: India, NA (negative NP%)
- Top Customers: Amazon, AtliQ eStore, AtliQ Exclusive
- Top Products: AQ Wi Power Dx Series

# 🎯 Business Impact & Value

This dashboard enables stakeholders to:
- Identify unprofitable markets & customers
- Improve pricing & margin strategies
- Monitor demand forecasting accuracy
- Control operational costs
- Track market share growth against competitors
- Make strategic decisions with confidence

# 📁 Project Files

[Power BI Dashboard (PBIX)](https://github.com/AlishaMahanty/AtliQ_Business_Insights_360/blob/main/
Excel Master Data
PDF Report (Business Insights 360)
