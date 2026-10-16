# Descriptive-Analytics-Project-
# Food Delivery Transaction Analytics

A descriptive analytics project based on a synthetic online food delivery transaction dataset.

## Overview
- Analyzes 2.26M simulated transactions across 60 delivery hubs.
- Explores KPIs, revenue trends, customer segments, regional demand, payment methods, and operational performance.
- Includes charts, insights, and business recommendations.

## Tools Used
- Python
- Pandas
- Matplotlib
- Excel

> **Note:** This project uses a synthetic dataset for educational and portfolio purposes.
> # IBM Cognos Analytics – RetailPulse Practicals

A set of six hands-on practicals in **IBM Cognos Analytics (Reporting & Dashboards)**, built around a fictional retail company, *RetailPulse*. They cover the full path from a first list report to an interactive customer dashboard.

## Practicals

| # | Practical | Topic |
|---|-----------|-------|
| 1 | [Generate a First RetailPulse Report](Practical_1_First_Report.pdf) | Intro to Cognos Reporting, running list report |
| 2 | [Build a Grouped Sales List Report](Practical_2_Grouped_List_Report.pdf) | Grouping, currency formatting, footer totals, page header |
| 3 | [Filter Sales by Region and Date](Practical_3_Filters.pdf) | Simple and advanced detail filters, prompted filter |
| 4 | [Region × Product Crosstab](Practical_4_Region_Product_Crosstab.pdf) | Crosstab, multiple measures, summary totals |
| 5 | [Sales Prompt Report](Practical_5_Prompt_Report.pdf) | Value, date-range and cascading prompts |
| 6 | [Customer Insights Dashboard](Practical_6_Customer_Insights_Dashboard.pdf) | KPI card, line chart, bar chart, cross-filtering |

Each PDF contains the objective, materials required, step-by-step procedure, an illustrative output, and the expected outcome.

## Tools & Data

- IBM Cognos Analytics
- RetailPulse Sales package (Practicals 1–5)
- RetailPulse Customers data module (Practical 6)

## Note

The output screens in the PDFs are illustrative mock-ups using sample figures, not live RetailPulse data.

## Skills Demonstrated

List and crosstab reports · grouping & aggregation · filters · prompt pages & cascading prompts · dashboard design and cross-filtering
# RetailPulse Power BI Practicals (7-10)

Lab work for **Business Analytics - IBM Cognos Analytics Unit**, covering Units 3 and 4 of the lab manual. All four practicals use the same fictional **RetailPulse** retail dataset (Sales, Product and Store tables) and build on one another: each practical continues from the `.pbix` file produced in the previous one.

## Contents

| # | Practical | Report | Unit |
|---|-----------|--------|------|
| 7 | Import and Transform RetailPulse Data in Power BI | [Practical_7_Import_Transform_RetailPulse.pdf](Practical_7_Import_Transform_RetailPulse.pdf) | 3 |
| 8 | Model, Calculate, and Publish a RetailPulse Sales Report | [Practical_8_Model_Calculate_Publish_RetailPulse.pdf](Practical_8_Model_Calculate_Publish_RetailPulse.pdf) | 3 |
| 9 | Time Intelligence and Advanced DAX for RetailPulse | [Practical_9_Time_Intelligence_DAX_RetailPulse.pdf](Practical_9_Time_Intelligence_DAX_RetailPulse.pdf) | 4 |
| 10 | Interactive Dashboard, Row-Level Security, and Power Platform Integration | [Practical_10_Dashboard_RLS_PowerPlatform_RetailPulse.pdf](Practical_10_Dashboard_RLS_PowerPlatform_RetailPulse.pdf) | 4 |

## Summary of each practical

### Practical 7 - Import and Transform Data
Explores the Power BI Desktop interface (Report, Table and Model views) and imports the Sales, Product and Store tables from an Excel workbook. In Power Query the data is cleaned: data types are set, blank and duplicate rows are removed, null quantities are replaced with 0, columns are renamed, and a conditional column **Sale Size** (Large if Sales Amount >= 1000, otherwise Standard) is added. The work is saved as `RetailPulse_Analysis.pbix`.
**Key concepts:** Import vs DirectQuery, Applied Steps, Power Query (M), data types.

### Practical 8 - Model, Calculate and Publish
Creates one-to-many relationships (Product -> Sales, Store -> Sales), writes the measures **Total Sales**, **Total Quantity** and **Average Order Value**, and adds the calculated column **Sales per Unit**. A report page is built with a card, bar chart, line chart and Region slicer, tested for cross-filtering, and published to the Power BI service.
**Key concepts:** star schema, measures vs calculated columns, `DIVIDE`, publishing and sharing.

### Practical 9 - Time Intelligence and Advanced DAX
Builds a Date table (`CALENDAR`), marks it as a date table and relates it to Sales. Creates **Sales YTD** (`TOTALYTD`), **Sales LY** (`SAMEPERIODLASTYEAR`), **YoY Growth %** (using `VAR`/`RETURN`) and **Region Share %** (`CALCULATE` with `ALL`), displays them in a matrix, and uses Performance Analyzer to find and reduce slow visuals.
**Key concepts:** time intelligence, filter context, variables, performance optimisation.

### Practical 10 - Interactive Dashboard, RLS and Power Platform
Adds slicers, a drill-through page (**Store Detail**) and bookmark buttons that toggle between chart and table views. Row-Level Security roles (**North Manager**, **South Manager**) are defined with DAX filters on the Store table and tested with *View as*. After publishing, roles are assigned in the Power BI service, a card is pinned to a dashboard, a data alert triggers a **Power Automate** flow (email/Teams), and a **Power Apps** visual shows the selected store's details.
**Key concepts:** drill-through, bookmarks, RLS, data alerts, Power Automate, Power Apps.

## Each report contains
- Objective and materials required
- Step-by-step procedure with observations
- DAX / Power Query code used
- Output tables and charts
- Expected-outcome check
- Viva-voce questions with answers

## Tools used
- Power BI Desktop and Power BI service
- Power Query (M) and DAX
- Power Automate and Power Apps (Practical 10)
- Dataset: `RetailPulse_Sales.xlsx` (Sales, Product, Store)

## Notes
- Figures and sample values in the PDFs are based on a sample RetailPulse dataset (Jan 2024 - Dec 2025). Results will differ slightly with a different workbook.
- Practical 10 Steps 4-6 require a Power BI Pro/Premium Per User licence and a work or school account.

## Repository structure
```
.
├── README.md
├── Practical_7_Import_Transform_RetailPulse.pdf
├── Practical_8_Model_Calculate_Publish_RetailPulse.pdf
├── Practical_9_Time_Intelligence_DAX_RetailPulse.pdf
└── Practical_10_Dashboard_RLS_PowerPlatform_RetailPulse.pdf
```

## Author
Name: ______________  Roll No.: ______________
