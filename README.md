# Pizza-Sales-Dashboard
## Pizza Sales Performance & Revenue Analytics Dashboard
An interactive, data-driven Power BI dashboard designed to analyze operational efficiency, sales trends, and consumer behavior for a high-volume pizza restaurant chain.

## Short Description / Purpose

The Pizza Sales Analytics Dashboard converts raw transactional point-of-sale (POS) data into actionable business intelligence. This tool provides comprehensive visibility into daily revenue streams, order volumes, and menu performance. It is specifically designed for restaurant managers and operators to track key performance indicators (KPIs), identify peak operational hours, optimize inventory procurement, and discover which pizza categories and sizes are driving the most bottom-line growth.

Tech Stack
=> Power BI Desktop: Used for UI/UX canvas design, visual hierarchy creation, and report publishing.

=> Power Query (M Language): Utilized for the Extract, Transform, Load (ETL) pipeline to clean messy order logs, parse date/time strings, and handle missing values.

=> DAX (Data Analysis Expressions): Leveraged for creating dynamic time-intelligence measures, calculating moving averages, and measuring percentage contributions of different pizza types.

=> Data Modeling: Structured using a Star Schema layout, connecting the central Order Details fact table with dimensions like Pizza Type, Size, and Time/Date tables.

Data Source
The insights are generated from a multi-table relational restaurant dataset containing thousands of granular transactional records:

=> Core Entities: Includes fields for Order ID, Quantity, Order Date, Order Time, Unit Price, Total Price, Pizza Size (S, M, L, XL, XXL), Pizza Category (Classic, Supreme, Veggie, Chicken), and Pizza Name.

=> Granularity: Itemized at the individual line-item level per order, allowing deep-dive tracking from seasonal monthly trends down to hourly rush periods.

Features / Highlights

STEP 1 - Start with the Business Problem
The restaurant management struggled to forecast kitchen prep work and manage inventory effectively, leading to high food waste during slow periods and stockouts of key ingredients during sudden rushes. Furthermore, without a centralized data tool, it was impossible to tell which specific pizzas were actually profitable versus which ones were just taking up menu space.

STEP 2 - Define the Goal of the Dashboard
The goal was to create a real-time operational dashboard that provides a "Single Source of Truth" for sales performance. It targets three main pillars: revenue optimization, order volume tracking, and menu engineering (identifying best/worst sellers).

STEP 3 - Walk Through the Key Visuals
=> Executive KPI Cards: Bold, high-level metrics at the very top showcasing Total Revenue, Average Order Value (AOV), Total Pizzas Sold, and Total Orders Placed.

=> Hourly & Weekly Trends: A bar chart showing the distribution of orders throughout the day (pinpointing the lunch and dinner rushes) and a line chart tracking sales across different days of the week.

=> Category & Size Analysis: Donut charts displaying the percentage contribution of each pizza category (Classic vs. Veggie vs. Chicken) and size preferences (e.g., Large vs. Medium).

=> Top 5 & Bottom 5 Sellers: Dynamic horizontal bar charts that instantly rank the highest and lowest performing pizzas by revenue and quantity sold.

STEP 4 - Highlight the Insight
By filtering the Hourly Trend alongside the Top 5 Sellers, the dashboard revealed a major operational bottleneck: while the dinner rush generated the highest overall revenue, the kitchen was losing money on slow preparation times for complex pizza categories (like "Supreme" variations) during Friday night peaks. Conversely, certain large-sized veggie options were heavily ordered on weekdays but lacked proper inventory backup.

STEP 5 - Show the Business Impact
With these insights, the management team can now successfully implement data-driven staff scheduling to handle peak weekend hours, run targeted promotions on low-selling items to clear inventory, and optimize the supply chain to ensure high-demand ingredients are never out of stock

SCREENSHORTS/DEMOS

Example:(https://github.com/Muaid569/Pizza-Sales-Dashboard/blob/main/Pizza%20Sales%20Dashboard.png)
