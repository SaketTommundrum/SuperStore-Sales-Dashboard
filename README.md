# SuperStore Sales Dashboard

A Power BI report that provides interactive visualizations of sales, profit, quantity sold and delivery performance for a fictional “Super Store” retail dataset. It enables managers and analysts to quickly assess business performance across regions, segments, product categories and time horizons, and even includes a short-term forecast for future sales.

## 📌 Short Description / Purpose

The Super Store Sales Dashboard consolidates historical sales data (2019–2020) and a 15‑day sales forecast into a single, interactive interface. It allows users to explore metrics such as total sales, profit, quantity sold and average delivery days across multiple dimensions (customer segment, region, payment mode, product category and sub‑category). An additional forecast page projects sales for the next two weeks, helping business users prepare for imminent changes in demand.

## 🛠️ Tech Stack

Power BI Desktop – Primary platform for building interactive visualizations.

Power Query – Employed for data transformation and cleaning prior to modeling.

DAX (Data Analysis Expressions) – Used for dynamic calculations, such as year‑over‑year comparisons and forecast measures.

Data Modeling – Relationships defined between order dates, product categories, regional hierarchy and transactional data enable rich slicing and filtering.

File Format – Report is delivered as a .pbit template for reuse; screenshots included are .png.

## 📚 Data Source

Dataset Source: The report uses a standard “Super Store” dataset commonly found in analytics tutorials (e.g., Kaggle). It includes fictional orders, product information and sales transactions across the United States.

### Business Problem

Retail managers often rely on static spreadsheets to analyze sales performance, limiting their ability to filter, compare or drill down on the fly. Decision makers need a dynamic dashboard that highlights top‑selling products, regional performance and profit drivers, while also providing short‑term forecasts for demand planning


### Goal of the Dashboard

Provide an interactive view of sales, profit and quantity metrics across segments, regions, payment modes and product categories.

Enable year‑over‑year comparison of monthly sales and profit to reveal seasonality and growth trends.

Offer a 15‑day sales forecast to inform short‑term inventory and staffing decisions.

Allow non‑technical users to drill down into the data easily and identify high‑performing states, categories and sub‑categories


### Walkthrough of Key Visuals

Top KPIs – Cards for Total Sales (≈1.6 M), Quantity Sold (≈22 K), Total Profit (≈175 K) and Average Delivery Days (≈4), updating with filters

Sales by Segment – Donut chart showing Consumer, Corporate and Home Office contributions

Sales by Region – Donut chart breaking down revenue across West, East, Central and South

Payment Mode Distribution – Donut chart summarizing sales by payment methods (Cards, COD, Online)

Monthly Sales & Profit YoY – Line charts comparing 2019 vs. 2020 for sales and profit, highlighting seasonal peaks and troughs

Sales by Category & Sub‑Category – Bar charts ranking categories (Office Supplies, Technology, Furniture) and top sub‑categories (Phones, Chairs, Binders) by revenue

Sales by Ship Mode – Bar chart contrasting Standard, Second Class, First Class and Same Day shipments

Sales by State – Map pinpointing revenue distribution across U.S. states

Forecast Page – A time‑series chart projecting sales for the next 15 days with confidence intervals, plus a bar ranking states by forecasted sales

Dynamic Slicers – Region selectors (Central, East, South, West) update all visuals simultaneously for focused analysis

Business Impact & Insights

Performance Monitoring – Enables leadership to track sales and profit in real time, identify seasonal patterns and benchmark YoY performance.

Targeted Marketing – Highlights high‑value segments (Consumer) and regions (West and East), guiding promotional efforts. Underperforming regions or segments can be targeted for improvement

Product & Inventory Planning – Identifies top categories (Office Supplies, Technology) and shipping modes, helping to optimize product mix and logistics.

Payment Strategy Optimization – Shows that COD transactions dominate; encouraging more card and online payments could improve cash flow and reduce operational risk.

Short‑Term Forecasting – The 15‑day forecast provides a proactive view of upcoming demand, supporting better stock management and staffing decisions.


### 🗒️ Usage Tips

Filter by Region or Segment to see localized performance.

Hover over line charts to inspect monthly values.

Click on map or bar charts to drill down further into sub‑regions or categories.

Switch to the Forecast page via the bottom navigation to review upcoming sales projections.

Use this dashboard as a centralized tool to make data‑driven decisions across operations, marketing and finance.

### Dashboard view
<img width="963" height="546" alt="Forecast Page" src="https://github.com/user-attachments/assets/c55efef7-05f3-4be5-bb8f-e3695327b328" />
<img width="965" height="540" alt="Insights Page" src="https://github.com/user-attachments/assets/df9501bf-883e-4779-829c-ab3b44da91ac" />

