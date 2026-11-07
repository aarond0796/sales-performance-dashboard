# Sales Performance Analytics Dashboard

An Excel dashboard that turns a small retail sales dataset into KPIs, pivot-table summaries and charts. I built it to practise a full analysis workflow in Excel: raw data, cleaning checks, calculations, pivot analysis and a one-page dashboard.

![Dashboard](dashboard.png)

> Add a screenshot of the Dashboard sheet as `dashboard.png` in this folder so it shows above.

## What's in the workbook

| Sheet | Purpose |
|---|---|
| **Raw_Data** | The original 20 orders (Jan-Feb 2025) with `Sales` and `Profit` calculated by formula |
| **Clean_Data** | Cleaned copy of the data, with a **Duplicate Check** and **Missing Data Check** on every row |
| **Analysis** | Headline metrics (revenue, profit, orders, average/highest/lowest sale, units sold, profit margin) plus sales and profit by region, all driven by formulas |
| **Pivot sheets** | Pivot tables for sales and profit by region, product, category and order date, with slicers for Region and Category |
| **Dashboard** | KPI cards (revenue, profit, orders, margin) and charts for sales by region, profit by region, sales by category and profit by category |

## Dataset

- 20 sample orders across 5 UK regions: London, Manchester, Birmingham, Leeds and Bristol
- 7 products in 2 categories (Electronics and Furniture)
- Fields: Order ID, Order Date, Region, Product, Category, Quantity, Unit Price, Unit Cost, Sales, Profit
- This is **sample data I created for practice**, not real company data

## Key results

- **Total revenue:** £10,840
- **Total profit:** £3,895
- **Profit margin:** 35.93%
- **Orders:** 20
- London is the top region by both sales (£3,210) and profit (£1,150)
- Electronics generates £8,680 of the £10,840 in sales

## Skills demonstrated

- Excel formulas: `SUM`, `SUMIF`, `COUNTA`, `COUNTIF`, `AVERAGE`, `MAX`, `MIN`, `IF`
- Data quality checks (duplicate and missing-value flags)
- Pivot tables and slicers
- Charts and dashboard layout
- Turning raw data into business metrics such as profit margin

## How to use

1. Download `Sales_Performance_Analytics_Dashboard.xlsx`
2. Open it in Microsoft Excel (slicers and pivot tables need desktop Excel or Excel for the web)
3. Start on the **Dashboard** sheet, then explore **Analysis** and the pivot sheets
4. To add data, add rows to **Clean_Data** and use **Data > Refresh All** to update the pivots

## Author

Aaron Donkoh: [github.com/aarond0796](https://github.com/aarond0796)
