# Power_BI_Dashboard_Brewing_Company_Sales_Dashboard
🍺 Seven Sages Brewing Company – Sales & Profitability Analysis (Power BI)
🚀 Overview
This project was completed as part of the Udacity Business Intelligence Nanodegree. It focuses on building a centralized data model and interactive Power BI report for Seven Sages Brewing Company (SSBC).
The goal was to integrate multiple data sources into a single, scalable data model that enables the CFO to quickly analyze:

Sales performance
Cost of sales
Profitability by product
Currency-adjusted financials


🧠 Business Problem
Seven Sages Brewing Company’s data was previously siloed across multiple sources, making it difficult to evaluate overall performance.
The CFO needs a reliable reporting solution to answer key questions such as:

Which beers generate the most revenue?
Which products are the most profitable?
How do results differ across currencies and time periods?


🎯 Project Objectives

Build a clean, scalable data model using multiple data sources
Enable multi-currency reporting (USD & CAD)
Calculate key financial metrics using DAX
Deliver an executive-friendly Power BI dashboard


🗂️ Data Model
The final model follows a star schema design:


Fact Table

Sales transactions (units sold, product, customer, date)



Dimension Tables

Customer
Product
Currency (exchange rates)
Date (custom fiscal calendar)



✅ All relationships are one-to-many, with filters flowing into the fact table.

🧹 Data Preparation
Data was cleaned and transformed using Power Query:

Merged and appended multiple source files
Standardized inconsistent formats and column names
Removed errors, null values, and duplicate fields
Fixed data issues (e.g., inconsistent worksheet names, missing currency values)


📅 Date Table
A custom date table was created to support time intelligence, including:

Calendar Year & Month
Fiscal Year (Oct 1 – Sept 30)
Fiscal Quarter (e.g., Q1 - FY2021)
Dynamic date range aligned with sales data


📊 Key Measures (DAX)
The following measures were created:
💵 Financial Metrics

Sales (USD $)
Cost of Sales (USD $)
Gross Profit Margin (%)

🌎 Multi-Currency

Sales (CAD $) using daily exchange rates

📈 Performance Metrics

Unit Sales by Product (%)
Share of Gross Profit by Product (%)


📊 Dashboard Overview
📄 Page 1: Sales Performance


KPIs:

Total Sales (USD): $167.57K
Total Sales (CAD): $224.21K
Gross Profit Margin: 14.7%



Matrix visualization:

Sales by customer type and fiscal quarter



Executive summary highlighting key trends



📄 Page 2: Product Performance

Breakdown of:

% of total sales by beer
% of total gross profit by beer



➡️ Helps identify:

High-revenue vs high-profit products
Opportunities for pricing or marketing adjustments


📈 Key Insights

Some products generate high sales but lower profitability, indicating potential pricing issues
Others contribute disproportionately to gross profit, presenting strong opportunities for promotion
Multi-currency reporting reveals the impact of exchange rate fluctuations on revenue


🛠️ Tools & Technologies

Power BI
Power Query (ETL)
DAX (data modeling and calculations)
Data modeling (star schema design)


💡 Business Recommendations

📢 Promote high-margin beers to maximize profitability
💰 Review pricing strategies for high-sales/low-profit products
🌍 Monitor exchange rate impact on revenue performance
📊 Use centralized reporting to support faster decision-making


▶️ How to Use

Open the .pbix file in Power BI Desktop
Navigate between report pages
Use filters to explore:

Customer types
Products
Time periods


Review KPIs and visuals for insights


📌 Final Takeaway
This project demonstrates how a well-designed data model and reporting layer can transform fragmented data into actionable insights.
The solution enables SSBC leadership to:

Improve decision-making
Identify profitable products
Optimize pricing and marketing strategies


🙋‍♀️ Author
Lydia Longanecker

GitHub: https://github.com/yourusername
LinkedIn: https://linkedin.com/in/yourprofile


📎 Acknowledgments
This project was completed as part of the Udacity Business Intelligence Nanodegree, using provided datasets and guided requirements.
