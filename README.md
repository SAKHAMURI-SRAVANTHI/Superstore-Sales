# Superstore-Sales
## Project Overview

This project presents an interactive Sales Dashboard developed in Power BI using the Superstore dataset. The dashboard provides insights into sales performance, profitability, customer segments, regional performance, and payment methods to support data-driven decision-making.

## Key KPIs
- Total Sales

- Total Profit

- Total Quantity Sold

- Total Orders

- Profit Margin %
## Dashboard Features
- Sales by Category

- Sales by Segment

- Sales by Region

- Monthly Sales Trend (YoY)

- Monthly Profit Trend (YoY)

- Sales by Payment Mode
## Interactive Filters for:
- Region

- Category

- Segment

- Order Date
## Tools Used
- Power BI

- Power Query

- DAX

- Microsoft Excel
## DAX Measures
* Total Orders = DISTINCTCOUNT(Sheet1[Order ID])

* Profit Margin % =
DIVIDE(
    SUM(Sheet1[Profit]),
    SUM(Sheet1[Sales]),
    0
)
## Dashboard Preview

<img width="1277" height="718" alt="image" src="https://github.com/user-attachments/assets/22ba0fbe-3894-4884-9293-688a762f66e8" />


## Business Insights
- Office Supplies generated the highest sales among product categories.

- Consumer segment contributed the largest share of sales.

- West region recorded the highest sales performance.

- The dashboard enables analysis of sales and profit trends across different months, regions, categories, and customer segments.

- Interactive filters allow users to explore business performance from multiple perspectives.
