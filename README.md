# Business Insights 360

## Overview
This Project is developed so as to provide 360-degree business solution for leading electronic company AtliQ to enhance decision making across different
domain by incorporating Power BI dashboard instead of heavily depending upon Excel. 

## Problem Statement:
With expansion ,AtliQ is experiencing challenges in managing its business operations globally.Analysis reports shows that Latin America is majorly affected 
because of its dependence upon Excel files for analytics 

## Objective:
The Aim was to develop an Integrated Business solution to empower Analytics of AtliQ by transititoning to Power BI dashboard from Excel and thereby improving 
decision making across various domains like Finance, Sales, Marketing and Supply chain

## Understanding the Dataset
Once the aim of project were clear , i took a glance of data provided by data engineering team. Let's take a view of datasets:

Dimension Tables
dim_customer: Includes static details like customer names, markets, and platforms (e.g., Online and Offline ).
dim_market: Contains information of distinct markets, sub-zones, and regions (APAC, EU, LATAM, and NAN).
dim_product: Shows product categories and divisions.

Fact Tables
fact_forecast_monthly: Holds forecasted customer demand for improved inventory planning and cost optimization.
fact_sales_monthly: Similar to the forecast table, but includes actual sold quantities.

Additional Tables
gross_price: Product pricing details.
freight_cost: Transportation costs for each market.
pre_invoice_deductions & post_invoice_deductions: Deductions applied before and after invoicing.
manufacturing_cost: Product manufacturing costs by year.


## Data Modeling
Data modeling is the foundation stone for any successful Power BI project.Snowflake schema is taken into account to optimize performance.If data modelling is
not done properly then it will significantly affect report performance so relationships and cardinality are given special focus.


## Tools Used
* Business Intelligence (BI)

* SQL

* Microsoft Excel

* Microsoft Power BI

* DAX (Data Analysis Expression)

* ETL (Extract, Transformation & Load)

* Data Modeling

* Data Visualization

* Microsoft Excel

* Power Query

## Features:

Home View: A landing page with buttons for navigation to different views
https://github.com/himanshusaxena11/Analytics/blob/3017767595a83dd88b7f3c9417c0d9986bb886aa/chapter-7-bi360%2012.pdf

Finance View: Show profit & loss statement to understand the financial performance across markets, products and customers
https://github.com/himanshusaxena11/Analytics/blob/3017767595a83dd88b7f3c9417c0d9986bb886aa/chapter-7-bi360%2012%20(2).pdf

Sales View: Analyze the customer performance like net sales and gross margin with dynamic charts and filters
https://github.com/himanshusaxena11/Analytics/blob/3017767595a83dd88b7f3c9417c0d9986bb886aa/chapter-7-bi360%2012%20(1).pdf

Marketing View: Evaluates product performance and maps profitability and growth potential
https://github.com/himanshusaxena11/Analytics/blob/3017767595a83dd88b7f3c9417c0d9986bb886aa/chapter-7-bi360%2012%20(3).pdf

Supply Chain View: Analyze forecast accuracy and net error metrics
https://github.com/himanshusaxena11/Analytics/blob/3017767595a83dd88b7f3c9417c0d9986bb886aa/chapter-7-bi360%2012%20(4).pdf

Executive View: A top-level dashboard consolidating insights for executives
https://github.com/himanshusaxena11/Analytics/blob/3017767595a83dd88b7f3c9417c0d9986bb886aa/chapter-7-bi360%2012%20(5).pdf

## Key Business Concepts Learned
This project also deepened my understanding of several key business terms, such as:

* Gross Margin: Sales minus the cost of goods sold.
* COGS (Cost of Goods Sold): Direct costs associated with producing goods.
* Net Invoice Sales (NIS): Revenue after pre- and post-invoice deductions.
* Gross Margin: A measure of profitability.
* Gross Margin %: Percentage of profit from sales.
* Market Share %: Company’s sales compared to the whole market.
* Forecast Accuracy: How close sales predictions are to actual sales.
* Net Error: Difference between actual and predicted results.
* Absolute Error: The exact difference between actual and predicted results.
* YTD (Year to Date) & YTG (Year to Go): Metrics to track progress over time.

## Project Outcome:
* Atliq's Sales: Despite an upward trend, Atliq's net sales fell short of the 2022 target.

* Net Sales Performance: In March 2020, net sales were lower compared to March 2019. However, post-March 2020, monthly net sales have steadily improved.

* Declining Networking Segment: The networking segment is experiencing the most significant decline in the EU region, particularly in France and the Netherlands. Understanding 
the reasons behind this decline is crucial.

* Notebook Division Growth: The notebook division is performing well in terms of net sales.

* Forecast Accuracy Decline: Forecast accuracy dropped sharply in 2021 due to COVID-19 restrictions, as customers avoided physical stores.

* Market Share Growth: Atliq Hardware's market share grew significantly, from 1.1% in 2021 to 5.9% in 2022.

## Live Dashboard:
Explore live dashboard : https://lnkd.in/dbkjJ5as

