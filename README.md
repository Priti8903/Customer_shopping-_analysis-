# Customer Shopping Behavior Analysis
## Project Overview
This project analyzes transactional data from 3,900 purchases to uncover key insights into customer spending patterns, demographics, and subscription behavior. By leveraging Python for data engineering and Power BI for visualization, this analysis provides actionable recommendations to optimize marketing strategies and improve customer retention.

## Dataset Summary
The dataset consists of 3,900 rows and 18 columns, covering:

Demographics: Age, Gender, Location, Subscription Status.

Transaction Details: Item Purchased, Category, Purchase Amount, Season, Shipping Type.

Behavioral Metrics: Review Ratings, Previous Purchases, Discount Usage, and Frequency of Purchases.

## Technical Workflow
1. Data Cleaning & Engineering (Python)
Using pandas and numpy, the data underwent a rigorous preparation process:

Handling Missing Values: Imputed 37 missing values in the Review Rating column using the median rating of their respective product categories.

Standardization: Converted column names to snake_case for consistency.

Feature Engineering: * Binned ages into age_group (e.g., 18-25, 26-35).

Created purchase_frequency_days to quantify customer return rates.

Customer Segmentation: Classified users into New, Returning, and Loyal segments based on purchase history.

## 2. Exploratory Data Analysis (EDA)
Key queries addressed during the analysis:

Revenue Drivers: Identified high-spending discount users and total revenue by age group.

Shipping Impact: Compared average purchase amounts between Standard and Express shipping.

Subscription Analysis: Evaluated whether frequent buyers (>5 purchases) are more likely to subscribe.

Product Performance: Identified the top 5 products by rating and the most "discount-dependent" items.

## 3. Data Visualization (Power BI)
An interactive dashboard was developed to transform raw data into visual stories.

Key Insights & Business Recommendations
Boost Subscriptions: Data shows a correlation between high purchase frequency and subscription potential; exclusive loyalty benefits should be targeted at these users.

Optimize Discounts: Identified specific products where sales are heavily reliant on discounts. A revised pricing strategy is recommended to protect margins.

Targeted Marketing: Focus marketing spend on the highest-revenue age groups and encourage the use of Express shipping, which correlates with higher transaction values.

Loyalty Programs: Implement rewards specifically for the "Returning" segment to transition them into "Loyal" customers.

<img width="1514" height="809" alt="image" src="https://github.com/user-attachments/assets/b70f0227-6d73-4ee0-b00f-5b4dc51b9f43" />


## Tools Used
Python: Data Cleaning, Feature Engineering, Data loading, EDA and Statistical Analysis.

Libraries: pandas, numpy,

SQL Server: Data querying and aggregation

Power BI: Interactive Data Visualization and Dashboarding.

Microsoft PowerPoint: Final presentation


