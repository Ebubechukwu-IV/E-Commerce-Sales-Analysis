# E-Commerce Sales Analytics

**Tools:** Microsoft Excel · Power BI
**Dataset:** Kaggle E-Commerce Practice Dataset
**Period:** January 2024 – June 2024
**Status:** ✅ Completed

---

## Dashboard Preview

![Executive Summary](https://github.com/Ebubechukwu-IV/E-Commerce-Sales-Analysis/blob/38760bb21a9072ef1164a9e6149dbf2d162d3265/Why%20%26%20How.png)
![Why & How](screenshots/why_and_how.png)
![Drill Down](screenshots/drill_down.png)

## Project Overview

This project analyses a retail e-commerce dataset to uncover revenue trends, product performance, and market insights across four countries. It is the first project in my public data analytics portfolio, built as part of my transition from Warehouse Operations into Data Analytics.

The analysis covers 360 orders, 40 products, and 115 active customers across the UK, US, Canada, and India — using Excel for data preparation and Power BI for interactive visualisation.

---


## Business Questions Answered

- Which product category generates the most revenue?
- Which market (country) drives the highest order volume and revenue?
- How does revenue trend month-over-month?
- Which products are top performers?
- How does average order value vary by category and country?
- What is the customer activation rate?

---

## Key Findings

| Metric | Value |
|---|---|
| Total Revenue | ₦249,314.65 |
| Total Orders | 360 |
| Units Sold | 1,080 |
| Average Order Value | ₦692.54 |
| Active Customers | 115 / 120 (95.8%) |
| Best Month | March — ₦52,091.57 |

### Revenue by Category

| Category | Revenue | Share | Avg Order Value |
|---|---|---|---|
| Electronics | ₦74,267.19 | 29.8% | ₦816.12 |
| Beauty | ₦49,960.63 | 20.0% | ₦724.07 |
| Sports | ₦44,843.46 | 18.0% | ₦560.54 |
| Home | ₦42,451.15 | 17.0% | ₦786.13 |
| Clothing | ₦37,792.22 | 15.2% | ₦572.61 |

### Revenue by Country

| Country | Revenue | Orders | Avg Order Value |
|---|---|---|---|
| United Kingdom | ₦86,879.59 | 136 | ₦638.82 |
| Canada | ₦57,774.68 | 70 | ₦825.35 |
| United States | ₦53,254.90 | 87 | ₦612.13 |
| India | ₦51,405.48 | 67 | ₦767.25 |

### Monthly Revenue Trend

| Month | Revenue |
|---|---|
| January | ₦38,121.72 |
| February | ₦36,272.57 |
| March | ₦52,091.57 ⬆ Peak |
| April | ₦37,290.87 |
| May | ₦33,711.56 ⬇ Trough |
| June | ₦51,826.36 ⬆ Recovery |

---

## Notable Insights

- **Electronics dominates everywhere** — the top category in all four markets without exception.
- **Canada punches above its weight** — only 23 registered customers, yet 70 orders and the highest AOV (₦825.35) of any market.
- **Home category is an outlier** — fewest units sold (179) but second-highest AOV (₦786.13), indicating premium pricing.
- **PROD024 is a standout** — ₦19,444.60 in revenue from a single product, accounting for ~7.8% of total revenue.
- **April–May dip** — revenue falls significantly after the March peak, worth investigating for seasonal or campaign-related causes.
- **95.8% customer activation rate** — 115 of 120 registered customers placed at least one order.

---

## Excel Techniques Applied

- Data cleaning and table structuring (Sales, Products, Customer Info)
- `XLOOKUP` — auto-populate product category from Products table
- `VLOOKUP` — pull unit price and customer country into Sales table
- `IF` validation logic — Revenue Per Order consistency check
- Pivot Tables — category, country, and monthly breakdowns
- KPI metric summary panel

## Power BI Techniques Applied

- Relationships across three tables (Sales, Products, Customer Info)
- DAX measures for Total Revenue, AOV, and Units Sold
- Slicers for Country and Category filtering
- Bar charts, line charts, and KPI cards in an interactive dashboard

---

## Files in This Repository

| File | Description |
|---|---|
| `Ecommerce_Analytics_Cleaned_Practice_Dataset.xlsx` | Cleaned dataset with formulas and Pivot Tables |
| `E-Commerce_Sales_Analysis.pbix` | Power BI dashboard file |
| `Ecommerce_Insight_Report.docx` | Full written analysis and recommendations |

---

## About This Project

This is Project 1 of my data analytics portfolio. I am a Warehouse Operations Manager transitioning into data analytics, currently progressing through Excel → SQL → Power BI. Each project is designed to build on real analytical questions and produce business-relevant insights.
