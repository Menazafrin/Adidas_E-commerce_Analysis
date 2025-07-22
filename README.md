# Adidas_E-commerce_Analysis
📌 **Project Objective**

The goal of this project is to analyze Adidas's retail sales data across various geographies, product lines, and sales methods. As a data analyst, the objective is to extract insights to support data-driven decisions in inventory management, pricing strategy, and marketing efforts.

📊 **Dataset Features**

The dataset simulates transactional e-commerce data with the following key attributes:
1. Retailer	-- Name of the retailer (e.g., Foot Locker)
2. Region   -- Region where the transaction occurred
3. State, City	-- Location details of the transaction
4. Invoice Date	-- Transaction date (standardized date format)
5. Product	-- Product description sold
6. Price per Unit	-- Price of each unit (numeric, currency symbols removed)
7. Units Sold -- Quantity sold
8. Total Sales -- Total revenue generated
9. Operating Profit	-- Profit after deducting operational costs
10. Operating Margin -- Profit as a % of sales
11. Sales Method -- Channel of sale (In-store, Outlet, Online)

🔧 **Data Preprocessing**

• Performed initial data cleaning in Excel and SQL before analysis:
• Removed currency symbols from Total Sales, Operating Profit, etc.
• Converted price and sales columns to proper numeric types
• Standardized Invoice Date into consistent YYYY-MM-DD format
• Trimmed extra spaces and formatted product/category names
• Addressed null values and outliers

🧠 **Analytical Techniques Used**

• CTEs and Window Functions
• Subqueries
• Aggregations & Filters

📈** Key Insights & Business Recommendations**

• Men's and Women's Footwear generated the highest revenue and profit margins — a priority for inventory and marketing investment.
• Regions like Northeast and West showed the highest units sold — ripe for targeted campaigns and promotions.
• Identified seasonal sales patterns, helping to align inventory and campaigns with high-demand months.
• Sales methods like in-store and outlet outperformed online in high-margin categories.


✅ **Tools Used**

• SQL (MySQL) – Analytical Queries, Window Functions, CTEs
• Excel – Initial preprocessing, data cleaning
• GitHub – Code versioning and project documentation

🔍** Outcome**

• This project demonstrated how raw transactional data can be transformed and analyzed using SQL to derive meaningful business intelligence. The analysis supports actionable decisions in product strategy, stock planning, and channel targeting.


