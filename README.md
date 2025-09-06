# Retail Store Analytics Dashboard

This repository contains a **Power BI dashboard** designed to provide comprehensive analytics for retail store performance. The dashboard visualizes essential metrics including sales, profit, returned orders, and in-depth breakdowns by product, state, and market segment.

## Features

- **Sales & Profit Tracking:** Monitor total sales and profit figures alongside year-over-year comparisons.
- **Returned Orders Analysis:** View the percentage of returned orders and their trend compared to previous periods.
- **Time Series Insights:** Analyze sales trends over time compared with previous years for better forecasting.
- **Profit by Product:** Examine profit margins across various product categories including Furniture, Office Supplies, and Technology.
- **Geographical Performance:** Visualize profit distribution across different US states to identify high-performing regions.
- **Segment Analysis:** Explore sales by customer segments, identifying key contributors to overall revenue.

## Dashboard Visuals

- **KPIs:** Sales, Profit, % Returned Orders
- **Bar Charts:** Profit by Product
- **Line Charts:** Sales Over Time (Current vs Previous Year)
- **Map Visualization:** Profit by State
- **Donut Chart:** Sales by Segment

## Data Model

The dashboard utilizes an Orders dataset, with fields such as:
- Category, City, Region, Order Date
- Product Name, Segment, Sales, Profit, Quantity
- State/Province, Customer Info, Discount Details

Additionally, calculated measures are included for year-over-year comparisons and percentage returns.

## Getting Started

1. Clone this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Connect to your retail dataset, matching the fields as shown in the dashboard.
4. Refresh visuals and perform your analysis.

## Customization

- Add new segments or product categories using the Orders data.
- Modify visual types to suit your analysis needs (e.g., swap bar chart for stacked column).
- Integrate additional KPIs for inventory, promotion impact, etc.

## License

This dashboard is MIT licensed for both commercial and non-commercial use.
