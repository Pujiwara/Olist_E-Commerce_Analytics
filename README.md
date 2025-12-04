# Olist_E-Commerce_Analytics

Project Title:
Olist E-Commerce Analytics

Description:
This project provides a comprehensive analysis of the Olist dataset—one of the largest e-commerce marketplaces in Brazil. The dataset includes orders, customers, sellers, products, payments, and reviews.
The main objective of this project is to build an end-to-end analytics workflow, starting from a PostgreSQL data warehouse, ETL transformations, and ending with an interactive Power BI dashboard used to explore key business insights.

Tools Used:
PostgreSQL
Power BI

Key Insights:
1. GMV Shows a Steady Growth Trend. Total GMV consistently increases over time, indicating strong marketplace performance.
2. Beleza & Saúde Category as the Main Growth Driver. This category has the highest GMV and the most orders. Its AOV (163) is slightly above the overall AOV (159), suggesting it is not only large in volume but also profitable.
3. Marketplace Is Not Dependent on Big Sellers. With 3,095 total sellers, the top 10 sellers contribute only around 14% of GMV. This indicates low concentration risk and a competitive market with evenly distributed seller contributions.
4. Delivery Performance Varies Across States. Some states show significantly longer delivery times (over 23 days), especially PA, AL, AM, AP, RR. This reflects logistical challenges in regions with difficult geographic access.
5. Logistics Operations Are Highly Efficient. Delivery Success Rate: 97.02%. On-Time Delivery: 96.30%. These high metrics demonstrate excellent operational performance.
6. Based on RFM Analysis: Majority of Customers Are in Potential & Loyal Segments. The number of Champions is relatively small, meaning retention strategies should focus on converting Potential & Loyal customers into Champions through loyalty programs, bundling, personalized campaigns, or behavior-based notifications.
7. Review Score Is Generally High but Negative Reviews Are Notable. Average rating is strong overall, yet negative review rate reaches 15%, with 11K one-star reviews out of 99K total reviews.

Dataset:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Data Warehouse Star Schema Components:
fact_orders, 
fact_order_items, 
fact_payments, 
fact_reviews, 
dim_customers, 
dim_sellers, 
dim_products, 
dim_dates, 
dim_geolocation (optional), 
rfm_segment

ETL Process (PostgreSQL & SQL):
The ETL pipeline includes several transformation steps such as:
Standardizing date formats, 
Cleaning and merging data for each table, 
Mapping keys between fact and dimension tables, 
Adding calculated attributes 

Power BI Dashboard Structure:
The cleaned and transformed data is imported into Power BI to create analytical dashboards with the following sections:
Summary Overview, 
Category Performance, 
Seller Performance, 
Customer & Delivery Performance, 
Review & Insights
