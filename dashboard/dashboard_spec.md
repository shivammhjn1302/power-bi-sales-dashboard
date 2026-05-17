# Power BI Dashboard Specification

## Page 1: Executive Sales Overview

### KPI Cards
- Total Sales
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin %

### Visuals
- Line chart: Sales by month
- Bar chart: Sales by region
- Column chart: Profit by category
- Donut chart: Sales by segment
- Table: Top products by sales

### Slicers
- Region
- Segment
- Category
- Month

## How to Build in Power BI

1. Import `data/cleaned/sales_dashboard_data.csv`.
2. Create measures from `dashboard/power_bi_measures.dax`.
3. Build visuals using this spec.
4. Save as `Sales_Dashboard_Beginner.pbix`.
