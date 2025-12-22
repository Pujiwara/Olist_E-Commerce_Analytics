# Olist E-Commerce Analytics

Project Title:
Olist E-Commerce Analytics

![page 1](https://github.com/Pujiwara/Pictures/blob/main/gmv%20olist_page-0001.jpg)
![page 2](https://github.com/Pujiwara/Pictures/blob/main/gmv%20olist_page-0002.jpg)
![page 3](https://github.com/Pujiwara/Pictures/blob/main/gmv%20olist_page-0003.jpg)
![page 4](https://github.com/Pujiwara/Pictures/blob/main/gmv%20olist_page-0004.jpg)
![page 5](https://github.com/Pujiwara/Pictures/blob/main/gmv%20olist_page-0005.jpg)

Description:
This case study presents an end-to-end analytics project using the Olist Brazilian E-Commerce dataset. The objective of the analysis is to evaluate marketplace performance from a GMV (Gross Merchandise Value) perspective while uncovering insights related to category performance, seller contribution, customer behavior, logistics efficiency, and review quality.
The project covers the full analytics lifecycle, starting from raw data ingestion, data staging, and dimensional data warehouse modeling in PostgreSQL, followed by analytical exploration and dashboard development in Power BI. The final output is an interactive dashboard designed to support executive-level decision-making.

Dataset:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

# Analytical Approach
### Methods
- **Data Modeling:**
    Star schema design with clearly separated fact and dimension tables to support analytical queries and BI reporting.
- **ETL & Data Transformation:**
    SQL-based transformations for cleaning, deduplication, aggregation, and key mapping.
- **Descriptive & Diagnostic Analytics:**
    GMV trends, category and seller contribution analysis, delivery performance evaluation, customer segmentation (RFM), and review quality assessment.
- **Business KPI Design:**
    Definition of core marketplace KPIs such as GMV, AOV, delivery success rate, on-time delivery, seller concentration, and customer segments.

### Dashboard Structure
1. **Executive Summary (GMV Overview)**
    High-level performance indicators and GMV trend.
2. **Category Performance**
    GMV, orders, AOV, and freight cost by product category.
3. **Seller Performance**
    Seller distribution, active sellers, GMV per seller, and seller concentration.
4. **Customer & Delivery Performance**
    Customer behavior, RFM segmentation, and logistics efficiency.
5. **Review & Quality Analysis**
    Review score distribution, negative review rate, and quality signals.

### Tools
- **PostgreSQL**
    - Raw, staging, and data warehouse schemas
    - SQL for ETL, transformations, and feature engineering
- **Power BI**
    - Data modeling & relationships
    - DAX measures for KPIs
    - Interactive dashboards and drill-down analysis

# Key Insight
- **GMV Shows a Stable Growth Trend**
    Total GMV increases consistently over time, indicating healthy marketplace expansion.
- **Highly Efficient Logistics Operations**
    Delivery success rate reaches 97.02%, while on-time delivery stands at 96.30%, indicating strong operational execution.
- **Beleza & Saúde Is the Main Growth Driver**
    This category records the highest GMV and order volume. Its AOV (163) exceeds the overall average AOV (159), signaling strong profitability alongside scale.
- **RFM Analysis Reveals Retention Opportunities**
    Most customers fall into Potential and Loyal segments, while Champions remain limited. This suggests a clear opportunity to focus retention efforts on upgrading existing customers.
- **Low Seller Concentration Risk**
    With 3,095 total sellers, the top 10 sellers contribute only around 14% of total GMV. This reflects a competitive marketplace with balanced seller participation.
- **Strong Review Scores with Notable Negative Feedback**
    Although the average review score is high, 15% of reviews are negative, with approximately 11K one-star ratings out of 99K total reviews.
- **Delivery Performance Varies Across States**
    Several states (PA, AL, AM, AP, RR) experience delivery times exceeding 23 days, highlighting logistical challenges in remote regions.

# Business Recommendations
- **Double Down on High-Performing Categories**
    Invest further in Beleza & Saúde through targeted promotions, exclusive campaigns, and supplier partnerships.
- **Strengthen Seller Enablement Programs**
    Since GMV is not concentrated among a few sellers, improving seller tools, logistics support, and analytics access can lift overall marketplace performance.
- **Improve Logistics in High-Risk States**
    Explore regional fulfillment hubs, alternative delivery partners, or differentiated delivery promises in states with long delivery times.
- **Customer Retention Strategy via RFM Segmentation**
    Design loyalty programs, personalized offers, and behavior-based communication to convert Potential and Loyal customers into Champions.
- **Leverage Review Data for Quality Improvement**
    Deep-dive into low-rating reviews to identify recurring issues related to product quality, delivery delays, or seller performance.
