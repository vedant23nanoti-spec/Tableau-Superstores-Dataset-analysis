# 🛒 Superstore Sales & Profitability Dashboard (Tableau)

An interactive Tableau dashboard analyzing the popular Superstore dataset to uncover sales performance, profitability, and regional trends across the business.

## 📌 Project Overview

This project analyzes 4 years of Superstore retail data to identify what's driving sales and where profitability is leaking. The dashboard enables stakeholders to interactively drill down by region, category, and time period to make data-driven decisions.

## 🎯 Objective

- Identify top and underperforming regions, categories, and products
- Analyze the relationship between discounting and profitability
- Build an executive-level interactive dashboard for quick decision-making

## 🗂️ Dataset

- **Source:** Superstore Sales Dataset (Kaggle/Tableau sample data)
- **Fields used:** Order Date, Region, State, Category, Sub-Category, Sales, Profit, Discount, Segment

## 🔧 Tools Used

- Tableau Public / Desktop
- Data blending & calculated fields
- Parameters and dynamic filters

## 📊 Dashboard Components

| Sheet | Purpose |
|---|---|
| Sales & Profit Overview | KPI summary (Total Sales, Profit, Orders, Margin %) |
| Regional Performance Map | Geo-map showing sales/profit by state |
| Category/Sub-Category Breakdown | Bar charts comparing performance |
| Trend Analysis | Monthly/yearly sales & profit trend lines |
| Discount vs Profit | Scatter plot showing impact of discounting on margins |

## 🧮 Key Calculated Fields

- Profit Margin = `SUM(Profit) / SUM(Sales)`
- YoY Growth = `(Current Year Sales - Previous Year Sales) / Previous Year Sales`

## 📈 Key Insights

- [e.g., "West region generates the highest profit despite moderate sales volume"]
- [e.g., "Furniture category has high sales but the lowest profit margin due to heavy discounting"]
- [e.g., "Discounts above 20% consistently result in negative profit on Sub-Category X"]


## 🧠 What I Learned

- Building executive dashboards with a clear visual hierarchy
- Using calculated fields to derive business metrics
- Balancing storytelling with interactivity in Tableau

## 📬 Contact

Connect with me on [LinkedIn](www.linkedin.com/in/vedant23nanoti) for feedback or collaboration.
