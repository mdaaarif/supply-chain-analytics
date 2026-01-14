# Supply Chain & Inventory Analytics Platform
This project analyzes supply chain, inventory, and logistics data to identify cost drivers, delivery bottlenecks, and inventory risks. 
Using SQL for analytical querying, Python for data preparation, and Power BI for visualization, the project delivers actionable insights 
to support inventory planning, supplier performance evaluation, and operational decision-making.
## Business Problem
Supply chain operations often suffer from delayed shipments, inefficient inventory turnover, and unreliable supplier performance.
This project addresses these challenges by analyzing transactional and operational data to:
- Detect delivery delays and lead-time bottlenecks
- Identify slow- and fast-moving products
- Forecast potential stock-out risks
- Support data-driven restocking and inventory planning
## Tools & Technologies
- SQL (MySQL): Core analysis, aggregations, window functions, KPIs
- Python: Data cleaning, preprocessing, and transformation
- Power BI: Interactive dashboards and reporting
## Dataset & Data Model
- Source: Public Kaggle dataset adapted for analytical use
- Data was restructured into a normalized relational schema

Main tables:
- orders
- products
- customers
- suppliers
- inventory
- shipments
## Analytical Approach
- Cleaned and prepared raw data using Python
- Designed SQL queries to analyze sales, inventory, and shipment performance
- Used window functions and CTEs to compute rolling metrics and rankings
- Built logic to detect stock-out risks and delivery delays
- Created Power BI dashboards to visualize KPIs and trends
## SQL Concepts Used
- Window Functions (ROW_NUMBER, RANK, LAG, LEAD, SUM OVER)
- Common Table Expressions (CTEs)
- Correlated and non-correlated subqueries
- Nested aggregations
- Date and time-based analysis for lead times and delays
## Key Analyses Performed
- Supplier on-time delivery performance analysis
- Identification of slow-moving SKUs by category
- Inventory turnover analysis at warehouse level
- Stock-out risk detection based on recent demand trends
- Rolling sales and returns analysis
- Supplier and product fulfillment ranking
- Restocking recommendation logic based on inventory signals
## Dashboard
Power BI dashboards were built to visualize:
- Sales and revenue trends
- Inventory health and turnover
- Supplier delivery performance
- High-risk products and stock-out alerts
