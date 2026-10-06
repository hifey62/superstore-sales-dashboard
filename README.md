# Superstore Sales Performance Dashboard

An interactive Power BI dashboard analysing four years of retail sales (2011-2014) across 51,290 order lines and 25,035 orders.

## Business questions
- How has sales performance changed over time?
- Is growth coming from more orders or bigger orders?
- Is the business staying profitable as it grows?
- Which products sell the most?

## Dataset
Global Superstore sales dataset (Kaggle), 51,290 rows.

## What I did
- **Cleaning (Power Query):** fixed a corrupted date column by sourcing a clean file, checked data types, text columns, nulls and duplicates (no duplicate rows found)
- **Data model:** built a Date table with DAX and a one-to-many relationship to Orders
- **DAX measures:** Total Sales, Total Profit, Profit Margin, Number of Orders, Average Order Value, Sales Last Year, Sales YoY %
- **Visuals:** KPI cards, sales trends by month with a year slicer, top 10 products

## Key insights
- Sales nearly doubled from 2.26M (2011) to 4.30M (2014), with YoY growth of 18.5%, 27.2% and 26.3%.
- Growth came from more orders (4,440 to 8,531), not bigger ones: average order value stayed flat at about 501-509.
- Profit margin held steady at 11-12% each year, with a small dip in 2014.
- Sales peak in November and December and are lowest in February.

## Screenshots
![Overview](overview.png)
![Trends](trends.png)
![Products](products.png)

## Tools
Power BI Desktop, Power Query, DAX
