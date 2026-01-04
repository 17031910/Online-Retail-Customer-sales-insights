Online Retail Supply Chain Analysis – Customer & Product Insights
Project Overview

This project analyses an online retail dataset to derive supply chain and inventory management insights. The goal is to identify demand trends, product performance, and stock optimization opportunities to support efficient replenishment, reduce stockouts, and improve overall supply chain performance.

The analysis uses Python (Google Colab) for data cleaning and exploratory analysis, and Power BI for interactive dashboards and decision-making support.

Dataset

The dataset contains transactional sales data with the following key fields:

Invoice Number

Product Description

Quantity & Unit Price

Invoice Date

Customer ID

Country

Data Preparation:

Removed records with missing product descriptions or customer IDs

Filtered out negative or zero quantities and prices

Converted invoice date to datetime format

Created derived fields: Total Revenue, Units Sold, Month, Year

Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn): Data cleaning, exploratory analysis, and visualizations

Google Colab / Jupyter Notebook: Interactive data analysis environment

Power BI: Interactive dashboards for monitoring demand, top products, and key supply chain metrics

Repository Files
File	Purpose
Online Retail.xlsx	Raw dataset containing sales transactions
Online_Retail_Customer_&_Sales_Insights.ipynb	Python notebook for data cleaning, inventory and demand analysis, and visualizations
Online_retail_supply_chain_report.docx	Professional report summarizing supply chain insights and recommendations
onlineretail_sales_insights.pbix	Power BI dashboards for interactive visualizations of demand, top products, and geographic sales distribution
Key Insights (Supply Chain Focus)

Demand Trends: Monthly demand peaks in November and dips in February → supports seasonal inventory planning

Top Products: Top 3 products account for 46% of total sales → prioritize stock and replenishment for high-demand items

Customer Behaviour: Average ~4 orders/year; repeat purchases indicate stable reorder patterns

Geographic Demand: UK dominates (~82%), international markets like Netherlands and EIRE show growth potential → informs regional inventory allocation

Supply Chain Recommendations

Inventory Planning & Replenishment:

Adjust stock levels according to seasonal peaks and product demand

Prioritize high-selling products for timely restocking

Demand Forecasting & Monitoring:

Use dashboards to monitor monthly sales, units sold, and reorder points

Predict low-demand periods to prevent overstocking

Product Portfolio Optimization:

Bundle slower-moving products with top sellers

Review non-product revenue items to improve stock tracking

International Logistics:

Allocate inventory strategically to international markets with potential growth

Optimize shipping and regional warehouses to reduce delivery times

Data-Driven Decision Making:

Leverage Power BI dashboards for continuous monitoring of demand, inventory levels, and supply chain KPIs

How to Use

Dataset: Open Online Retail.xlsx to explore raw sales data.

Python Analysis: Run Online_Retail_Customer_&_Sales_Insights.ipynb in Google Colab to reproduce metrics, demand trends, and visualizations.

Power BI Dashboards: Open onlineretail_sales_insights.pbix to interactively explore demand, top products, and geographic distribution.

Report: Refer to Online_retail_supply_chain_report.docx for a detailed professional report with insights and supply chain recommendations.

Conclusion

This project highlights critical supply chain insights, including demand patterns, top-selling products, and geographic trends. By leveraging these insights, the business can optimize inventory, plan for seasonal demand, and allocate resources efficiently, leading to improved operational efficiency and sustainable growth.
