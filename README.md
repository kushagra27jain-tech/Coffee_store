Coffee House End-to-End Business Intelligence Pipeline

Project Summary
I made a system to help a coffee shop chain with 3 stores see how well they are doing with sales and what people like to buy. I did not just use a tool to
make pictures I also did the hard work of getting the data ready and making sure it is correct. I used a MySQL database. Wrote special instructions, in SQL 
to load the data make tables and do complicated math to see how the coffee shops are growing. This way the final reports are easy to use. Will work well
even if the coffee shop chain gets really big.

Key Features & What I Did:
Database Design & ETL: Set up a clean relational schema in MySQL to store granular daily transaction records securely.
Feature Engineering: Grouped exact raw transaction timestamps into custom daily shift blocks (Morning, Afternoon, Evening) to help management map peak rush hours easily.
Advanced SQL Calculations: Used Common Table Expressions (CTEs) and SQL Window Functions (LAG()) to calculate dynamic Month-over-Month (MoM) sales growth directly in the database layer.
Dual-Theme Dashboards: Designed two distinct interactive views (a Light mode for C-suite executive performance and a Dark mode for detailed product category management)
Actionable Insights: Discovered that a small group of products drives over half the revenue (the 80/20 Pareto rule) and used this data to propose targeted business strategies like labor rescheduling and breakfast menu bundles.

Tech Stack Used:
Database Engine: MySQL Server
Languages: SQL (CTEs, Window Functions, Views, DDL/DML script execution)
Front-End Reporting: Interactive BI Dashboard Engine

Core Business Impact:
Revenue Growth: The business successfully scaled its monthly operations, showing a massive 104% revenue increase from January to June.
Store Performance: Business risk is safely diversified because sales are evenly balanced at around $230K per store across all three locations.
Rush Hour Staffing: Since 10:00 AM is the absolute peak rush hour, management can cut customer wait times and prevent lost sales by scheduling extra staff specifically during the morning window.
Inventory Safety: Because 20% of the products drive 57% of total revenue, the inventory manager must keep extra safety stock of high-tier items like espresso to protect daily cash flow.
Menu Combo Bundling: With a current Average Order Value of $4.82, creating breakfast meal combos will encourage upselling and easily unlock thousands of dollars in extra revenue from existing customers.


A project by Kushagra Jain
