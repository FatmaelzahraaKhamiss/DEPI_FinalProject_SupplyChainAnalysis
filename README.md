# DEPI_FinalProject_SupplyChainAnalysis
## Retail Stores Inventory and Demand Forecasting Project
### 1. Project Description
This project focuses on establishing data quality and accuracy for the "Retail Store Inventory and Demand Forecasting" dataset (2022 to 2024). The core objective was to make the data suitable for subsequent analytical and modeling tasks. This was achieved through a robust Data Preparation process, which involved transforming the raw CSV file into a flexible Star Schema, followed by comprehensive Data Cleaning utilizing Python libraries such as Pandas and NumPy.
### 2. Contents
The complete details of the Data Preparation and Cleaning procedures, including the process for dimensional modeling (Star Schema Generation), data type optimization, handling missing values, and outlier correction (negative prices), are fully documented and available in the attached Supply Chain Technical Report.
The actionable business insights, dashboards, and strategic recommendations are fully detailed in the Business Insights Report.
### 3. Data Findings
Following the successful cleaning and dimensional modeling, an in-depth exploratory analysis was conducted to identify key patterns, operational inefficiencies, and deliver actionable business insights.
#### A. Financial and Sales Performance Insights
These insights focus on core business metrics, operational performance, and regional dominance:
•	Major Fulfillment Gap: A critical discrepancy was identified where 45 million units were ordered, but only 21 million units were actually sold. This gap suggests a severe issue in order fulfillment or initial demand forecasting accuracy.
•	Regional Performance: The North region is the strongest sales performer (40.0% of total sales) and has the highest Inventory Turnover Rate. The South region registers the lowest turnover rate.
•	Sales Trend: Most months in 2023 showed an increase in sales compared to their 2022 counterparts, indicating a period of growth.
#### B. Customer, Pricing, and External Factors Insights
These insights focus on customer response, pricing strategy effectiveness, and crisis resilience:
•	Promotional Effectiveness: Promotional offers show a positive sales effect, with a Promo Period Uplift of 0.26. The average discount rate is $12.14$.
•	Customer Satisfaction Drivers: Customer ratings were found not to be correlated with the financial value of their purchases (e.g., Total or Quantity). This highlights the importance of service experience and store quality over transaction size.
•	Crisis Resilience: The average sales drop during the pandemic was 60.16%. However, the Pearson correlation between the pandemic flag and overall demand is 0.00, suggesting the pandemic shifted how sales occurred rather than eliminating demand entirely.
•	Top Crisis Category: The Groceries category demonstrated the highest resilience and demand during the pandemic period.


