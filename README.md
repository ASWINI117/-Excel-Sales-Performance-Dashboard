from pathlib import Path

content = 📊 Excel Sales Performance Dashboard

A beginner-friendly data analytics project built using Microsoft Excel to clean sample sales data, calculate key performance indicators (KPIs), and visualize sales performance by region and product.

## 📌 Project Overview

This project demonstrates a basic sales reporting workflow in Excel. The sample dataset contains order IDs, products, regions, and sales values. The data was cleaned and summarized to create a dashboard that makes key sales metrics easier to understand.

> **Note:** This is a learning/portfolio project using sample data. The results should not be interpreted as real business performance.

## 🎯 Project Objectives

- Prepare and clean a sample sales dataset.
- Identify and remove duplicate records.
- Handle missing region values.
- Summarize sales using Excel formulas and PivotTables.
- Present key metrics and comparisons in a dashboard.

## 🧰 Tools Used

- **Microsoft Excel**
- Excel Tables and data formatting
- Excel formulas
- PivotTables and PivotCharts
- Conditional formatting

## 🧹 Data Cleaning

The following preparation steps were performed:

- Reviewed the sample sales data.
- Removed a duplicate record based on the duplicate order entry identified during cleaning.
- Filled blank Region values with `Unknown`.
- Kept the missing Sales value blank rather than assuming an unknown value was zero.
- Formatted the cleaned data as an Excel table.
- Applied conditional formatting to help inspect sales values.

## 📈 Dashboard Features

### KPI Cards

- **Total Sales** — sum of the sales values included in the calculation.
- **Average Sales** — average of the sales values included in the calculation.
- **Highest Sale** — highest sales value.
- **Lowest Sale** — lowest sales value included in the calculation.

### Charts

- **🌍 Region-wise Sales Performance** — compares sales across regions.
- **🍩 Product-wise Sales Contribution** — shows each product's share of sales.
- **🛍️ Product-wise Sales Comparison** — compares sales across products.

The dashboard was created on a separate `Dashboard` worksheet, with the cleaned source data stored on the `Cleaned_Data` worksheet.

## 📁 Repository Structure

A suggested repository layout:

```text
Excel-Sales-Performance-Dashboard/
├── README.md
├── Excel_Sales_Performance_Dashboard.xlsx
└── screenshots/
    ├── dashboard.png
👩‍💻 Author

Aswini A
Aspiring Data Analyst
