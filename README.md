# Automated Sales MIS & Performance Reporting System

## 📊 Project Overview

The **Automated Sales MIS & Performance Reporting System** is an end-to-end business reporting and analytics project developed using Microsoft Excel and Power Query.

The project transforms transaction-level sales data into a structured reporting system containing KPI calculations, MIS reports, performance analysis, PivotTables, PivotCharts, slicers, and an interactive management dashboard.

## 🎯 Project Objective

The objective of this project is to reduce repetitive manual sales reporting work by creating a standardized and refreshable reporting workflow.

The system covers:

- Data cleaning and transformation
- Master-data mapping
- KPI calculation
- Monthly sales analysis
- Regional performance analysis
- Product performance analysis
- Salesperson performance analysis
- MIS reporting
- Interactive dashboard reporting
- Data validation and reconciliation

## 🏢 Business Problem

Sales transaction data often requires repeated cleaning, master-data mapping, financial calculations, monthly summaries, performance analysis, and dashboard preparation.

This project provides a structured Excel-based workflow to transform raw sales transactions into management-ready information.

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query
- Excel Tables
- Excel Functions
- PivotTables
- PivotCharts
- Slicers
- Dashboard Design
- Data Validation & Reconciliation

## 📁 Data Source

The project uses a **2026 CSV containing 5,000 sales transactions**.

### Source Fields

- Order ID
- Order Date
- Customer ID
- Salesperson
- Product ID
- Quantity
- Discount %
- Order Status

### Master Data

Five Excel master tables are used:

1. Customer Master
2. Product Master
3. Salesperson Master
4. Geography Master
5. Status Master

## 🔄 Project Workflow

**CSV Source → Power Query → Master Data Mapping → Clean_Data → Calculations → MIS Reports → Performance Analysis → PivotTables & PivotCharts → Interactive Dashboard**

## 🔧 Power Query Transformation

Power Query is used to:

- Import the sales CSV
- Correct date interpretation
- Convert data types
- Merge Customer Master
- Merge Geography Master
- Merge Product Master
- Merge Salesperson Master
- Expand required master-data fields
- Create Discount Amount
- Create Sales Amount
- Create Cost Amount
- Create Profit
- Produce the final 5,000-row Clean_Data dataset

The final Clean_Data dataset contains **20 columns**.

## 📐 Excel Calculations

Key Excel functions and techniques used include:

- XLOOKUP
- COUNTIF
- COUNTIFS
- SUMIFS
- INDEX + MATCH
- IFERROR
- EDATE
- MAX
- LARGE
- ROWS
- GETPIVOTDATA

These are used for KPI calculations, conditional aggregation, performance identification, monthly analysis, ranking, and interactive dashboard KPIs.

## 📊 MIS Reports

The project includes standardized MIS reporting for:

- Executive KPI Summary
- Monthly Performance
- Regional Performance
- Product Performance
- Salesperson Performance

## 📈 Interactive Dashboard

The final dashboard contains:

- 8 KPI Cards
- 6 PivotCharts
- 4 Slicers

### KPI Cards

**Fixed overall KPIs**

- Total Sales
- Total Profit
- Profit Margin
- Average Order Value

**Interactive KPIs**

- Total Orders
- Completed Orders
- Returned Orders
- Cancelled Orders

### Dashboard Visuals

- Monthly Sales & Profit Trend
- Regional Sales & Profit Performance
- Top 5 Products by Sales
- Salesperson Performance
- Order Status Analysis
- Category-Wise Sales

### Slicers

- Region
- Category
- Salesperson
- Order Status

## 📌 Key Project Results

| KPI | Result |
|---|---:|
| Total Orders | 5,000 |
| Completed Orders | 4,492 |
| Returned Orders | 144 |
| Cancelled Orders | 364 |
| Total Quantity | 14,759 |
| Completed Sales | ₹13,796,429 |
| Completed Profit | ₹5,850,929 |
| Profit Margin | 42.41% |
| Average Order Value | ₹3,071.33 |

## 🔎 Key Business Insights

- Highest Sales & Profit Region: **South**
- Highest Sales & Profit Product: **Grooming Kit**
- Highest Quantity Product: **Notebook Set**
- Highest Sales & Profit Salesperson: **Vikram Singh**
- Highest Profit-Margin Salesperson: **Rahul Verma**

These observations are descriptive results from the project dataset.

## ✅ Validation & Quality Checks

The project includes validation checks for:

- Order-status reconciliation
- Sales, cost and profit reconciliation
- Transaction-level calculation accuracy
- Monthly totals
- Regional totals
- Product totals
- Salesperson totals
- Fixed KPI behavior
- Interactive KPI and slicer behavior

## 🔄 Refresh Workflow

When source transactions or relevant master records are updated, the Power Query layer can be refreshed and the downstream calculation and PivotTable layers can be refreshed to reflect updated data.

## 📂 Project Files

| File | Description |
|---|---|
| Excel workbook | Complete Automated Sales MIS reporting system |
| PDF report | Detailed project documentation |
| CSV file | Source transaction data containing 5,000 records |

## 📄 Project Report

The detailed project report is available in:

**`Final_project2_Report.pdf`**

## 🎓 Skills Demonstrated

- Sales MIS & Management Reporting
- Advanced Excel
- Power Query
- Data Cleaning & Transformation
- Master Data Mapping
- Excel Formula Development
- Conditional Aggregation
- PivotTable & PivotChart Analysis
- Interactive Dashboard Development
- Slicer Design
- KPI Development
- Data Validation & Reconciliation
- Business Performance Analysis

## 👤 Project Author

**Chandankumar S B**

**Role Focus:** MIS Executive / Data Analyst / Report Analyst

---

*This project was developed as a personal portfolio project for practical learning and professional demonstration.*
