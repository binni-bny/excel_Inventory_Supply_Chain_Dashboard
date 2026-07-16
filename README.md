# Inventory & Supply Chain Management Dashboard

Excel-based analytics dashboard analyzing 180,000+ retail orders — powered by Power Query ETL, formula-driven KPIs, and Goal Seek scenario modeling.

## Overview

An Excel workbook that cleans, analyzes, and visualizes order, inventory, and delivery data from a global retail supply chain (DataCo Global). It answers real operational questions: which categories and markets drive the most revenue, how delivery performance varies by shipping mode, and how much on-time delivery could realistically improve through operational changes.

## Features

- KPI Dashboard with 11+ live-calculated metrics (sales, profit, margin, delivery performance, cancellation/fraud rates)
- Category, Market, and Monthly Trend breakdown tables (50 categories, 5 markets, 37 months)
- Delivery performance analysis by shipping mode, including on-time vs late rate comparison
- Goal Seek scenario model quantifying the maximum achievable on-time delivery improvement
- Bar, pie, line, and column charts built directly from formula-driven tables
- Full data cleaning pipeline via Power Query (column removal, type correction, deduplication)

## Skills Demonstrated

- Power Query (data import, transformation, type correction, custom columns)
- Excel formulas: SUMIF/SUMIFS, COUNTIF/COUNTIFS, AVERAGEIF
- What-If Analysis (Goal Seek) for scenario modeling
- Table-based data architecture (structured references)
- Data visualization (bar, pie, line, column charts)
- Data cleaning and PII handling
- Real-world dataset analysis (180,519-row Kaggle dataset)

## Key Insights

- Overall on-time delivery rate is 40.9%, with First Class shipping performing worst (0% on-time, 95.3% late)
- Goal Seek modeling shows shifting all First Class volume to Standard Class raises on-time delivery to 49.76% — the ceiling achievable through this lever alone, since First Class is only ~15% of total order volume
- Fishing, Cleats, and Camping & Hiking are the top 3 categories by sales
- Europe and LATAM are the largest markets by revenue

## Data Source

[DataCo Smart Supply Chain Dataset](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) (Kaggle) — 180,519 order-item rows, Jan 2015–Jan 2018. PII fields (email, password, name, street address) were removed during cleaning.

## File

📊 [Inventory_Supply_Chain_Dashboard.xlsx](Inventory_Supply_Chain_Dashboard.xlsx)
