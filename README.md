Superstore Sales Performance Dashboard

Superstore Sales Analytics project. It highlights your full tech stack (Python, SQL, and Power BI) and presents the project in a way that looks great to recruiters or open-source contributors.

Superstore Sales Performance Dashboard
An end-to-end data analytics project that transforms raw retail data into actionable business insights. This project leverages Python for data cleaning, SQL for data modeling and querying, and Power BI for interactive dashboard design to analyze sales, profit margins, and customer segments.


📌 Project Overview
This project analyzes a comprehensive Superstore dataset to uncover deep insights into sales trends, profitability, customer behavior, and regional performance. The goal is to identify key drivers of business growth, spot operational inefficiencies (such as high-discount/low-profit segments), and provide data-driven recommendations for stakeholders.

Key Insights Tracked:
KPI Metrics: Total Profit ($286.40K), Total Quantity Sold (38K), Total Sales ($2.30M), and Total Discount given (1.56K).

Product Performance: Evaluation of top-performing sub-categories (e.g., Copiers, Phones) against overall profitability.

Temporal Trends: Multi-year sales growth trajectories from 2014 to 2017.

Customer & Market Segmentation: Profit distribution across Consumer, Corporate, and Home Office segments, alongside a breakdown of top revenue-generating customers.

🛠️ Tech Stack & Workflow
1. Data Cleaning & Preprocessing (Python)
Libraries Used: pandas, numpy

Handled missing values, standardized data types, and parsed date columns (Order Date, Ship Date) for seamless time-series analysis.

Removed duplicate entries and engineered custom metrics like profit margins.

2. Data Modeling & Structured Queries (SQL)
Imported the cleaned dataset into a relational database.

Wrote complex SQL queries, aggregations, and CTEs (Common Table Expressions) to verify data integrity and extract summary metrics.

Optimized data schemas to ensure efficient loading into Power BI.

3. Data Visualization & Analytics (Power BI)
Data Transformation: Utilized Power Query for final data reshaping and schema normalization.

DAX Modeling: Created calculated measures for dynamic KPIs, year-over-year (YoY) growth, and running totals.

UI/UX Design: Implemented a modern, dark-themed UI featuring intuitive slicers (State, Ship Mode, Region) for dynamic stakeholder reporting.

📊 Dashboard Architecture & Visuals
The dashboard is split into distinct analysis zones to guide the end-user:

Executive Summary KPI Cards: Found at the top for an instant snapshot of core business health (Profit, Quantity, Sales, Discount).

Product & Category Analysis: A horizontal bar chart detailing Sum of profit by sub_category and a donut chart breaking down Sales by Category (Technology, Furniture, Office Supplies).

Sales Trend over Time: A line chart depicting Sum of sales by Year showing steady upward growth leading into 2017.

Customer Insights: A dedicated Top 10 Customers by Sale tracker to isolate high-value clients.

Operational Health: A granular Profit by Year timeline to identify specific seasonal drops or sudden losses.
