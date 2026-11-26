# Sales Dashboard - Power BI

An interactive two-page sales dashboard analyzing 260 orders across four Egyptian cities (Cairo, Giza, Alexandria, Tanta), built in Power BI with a custom dark-navy background design and sidebar page navigation.

## Dataset

- **Sales** - 260 orders: OrderID, OrderDate, ShipDate, ProductID, EmployeeID, Quantity, UnitPrice, Discount, OrderStatus (Completed / Cancelled / Returned), City
- **Products** - 18 products across Electronics, Furniture and Stationery, with cost and supplier country
- **Employees** - 10 sales reps with department, region and hire date

## Pages

**Overview**
- 6 KPI cards: Total Revenue 4M, Total Cost 3M, Net Profit 634K, Profit Margin 16%, Number of Orders 260, Total Quantity 1.51K
- Revenue LY with YoY growth % by month
- Revenue by order date vs ship date (monthly trend)
- Revenue YTD vs previous month
- Total revenue by city

**Products**
- KPI cards: Total Revenue, Distinct Products Sold (18), Avg Unit Price (3.01K)
- Employee performance table (orders, revenue, performance tier)
- Product profitability table (cost, revenue, net profit, margin %)
- Revenue by order type (Regular vs Bulk)
- Revenue and net profit by category

## Key Insights

1. Electronics drives ~77% of total revenue (3.15M of 4.07M) at the lowest category margin (15% vs Furniture's ~18%) - a revenue-concentration and margin tradeoff.
2. One product, Laptop Pro 15, brings ~45% of all revenue (1.84M) at a ~14% margin, one of the lowest in the catalog.
3. Bulk orders account for ~31% of revenue (1M of 4M), suggesting room to grow the bulk channel.
4. Giza and Cairo lead regional revenue (~28% and ~27%, over half combined), while Tanta is the smallest region at ~21%.
5. All sales reps hit the Excellent performance tier, with Nour Fathy leading at 48 orders and ~928K revenue.

## Tools & Techniques

- **Power BI**: data modeling across 3 tables, DAX measures (revenue, cost, profit, margin %, YoY growth, YTD/PM), slicers (Year, City, Quarter, Department, Category, Order Status)
- **Design**: custom JSON theme, background layout designed outside Power BI and set as page wallpaper, transparent visuals placed over card slots, blank buttons with page navigation over sidebar icons

## Screenshots

| Overview | Products |
|---|---|
| ![Overview](overview.png) | ![Products](products.png) |
