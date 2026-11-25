#  Sales & Performance Dashboard (Power BI)

## Project Overview
An interactive Power BI Desktop dashboard built using a Kaggle Sales dataset to track revenue, profit margins, regional performance, and product category trends.

## Key Business Questions Answered
* **Overall Health:** How are Total Sales ($2.30M), Total Profit ($286.4K), and Profit Margin (12.4%) trending Year-over-Year?
* **Seasonality:** Which months generate the highest sales volume versus the highest profit margins?
* **Product Mix:** Which categories and sub-categories drive revenue, and which ones suffer from margin erosion?
* **Geographic Performance:** Which states and regions are the most profitable markets?

## Tools & Techniques Used
* **Power Query Editor:** Data cleaning, null removal, data type standardization, and custom margin columns.
* **DAX Measures:** `SUM`, `DISTINCTCOUNT`, `DIVIDE`, and time-intelligence calculations (`SAMEPERIODLASTYEAR`) for YoY comparisons.
* **Data Visualization & Interactivity:** Combo charts, conditional bubble maps, data-bar matrices, dynamic slicers, and custom hover tooltips.

## Files in This Repository
* `Sales_Performance_Dashboard.pbix` – Full Power BI Desktop source file.
* `Sales_Performance_Dashboard.pdf` – Static PDF export for quick viewing.
* `dashboard_overview.png` – High-resolution screenshot of the main report page.

## Dataset Source
* Data sourced from [Kaggle Superstore Sales Dataset](https://www.kaggle.com/).
