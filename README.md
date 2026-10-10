# Croma Sales & Profit Dashboard (Excel)

Interactive Excel dashboard that analyses sales, profit, customers, product sub-categories and state-wise performance for an electronics retail business.

> **Dataset:** simulated Croma-style electronics retail data (2,000 orders) created for learning and portfolio purposes. It is not real or confidential Croma data.

![Dashboard](Dashboard.png)

## Dataset
- 2,000 orders, **Jan 2023 – 30 Aug 2026**
- 30 customers, 15 states, 5 categories, 12 sub-categories, 49 products
- Columns: Order Date, Customer Name, State, Country, Category, Sub-Category, Product Name, Sales, Quantity, Profit, Month, Year

## Key Insights
- **Total Sales ₹10.75 Cr and Total Profit ₹1.31 Cr**, a **12.2% profit margin**, across 2,000 orders.
- **Laptops, Televisions and Smartphones bring in ~65% of sales** (Laptops lead with ₹2.67 Cr). The 6 smallest sub-categories together contribute only ~15%.
- **TVs & Entertainment is the most profitable category** (₹38.0 L profit, 13.3% margin). Computers & Accessories has the highest sales but a lower margin (11.3%).
- **Small Appliances has the best margin (15.5%)** but only 7.6% of sales, a growth opportunity.
- **Profit margin improved from 11.5% (2023) to 13.7% (2026).** 2026 profit (₹35.2 L, data up to 30 Aug) has already passed full-year 2023 (₹34.0 L), even though sales were lower than in 2023.
- **Delhi is the top state** with ₹95.3 L sales (8.9% of total). Sales are spread fairly evenly across 15 states.
- **Top 5 customers (of 30) generate 23% of total profit.** Siddharth Das is the top customer with ₹7.64 L profit.
- **121 orders (6%) were loss-making**, totalling ₹2.41 L in losses, which is worth a pricing/discount review.

## Dashboard Features
Total Sales & Profit KPIs · Profit by Year · Sales by Sub-Category · Customer Records by Year · Sales by State (Map Chart) · Top 5 Customers by Profit · Sales by Month · Category, Year and Month slicers

## Tools & Techniques
Excel · PivotTables · PivotCharts · Slicers · Map Chart · Formulas · Data Cleaning

## Data Notes
- 2026 data runs only until 30 Aug, so "Sales by Month" shows lower values for Sep–Dec (those months have 3 years of data, Jan–Aug have 4). Use the Year slicer for fair comparisons.

## Files
- `Croma_Sales_Profit_Dashboard.xlsx` – workbook with the dataset, pivot tables and dashboard
- `Dashboard.png` – dashboard screenshot

## Author
Tejas Kadam – [LinkedIn](https://linkedin.com/in/tejas-kadam-b0983b2a6)
