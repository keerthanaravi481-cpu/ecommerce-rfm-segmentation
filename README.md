# E-commerce Customer Segmentation (RFM Analysis)

> Customer segmentation using RFM analysis (SQL CTEs + window functions, Python) to identify high-value and at-risk e-commerce customers for targeted marketing.

## Objective
Segment customers by Recency, Frequency, and Monetary value to inform targeted
marketing and retention strategy.

## Dataset
[E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data) (Kaggle)

## Tools
Python (Pandas), SQL (CTEs, NTILE window function), Google Colab

## Process
1. Cleaned transaction-level data (removed cancellations, missing CustomerIDs)
2. Used SQL to calculate frequency/monetary scores; Pandas for recency
3. Segmented customers into groups: Champions, Loyal Customers, At Risk, Needs Attention

## Key Insights
- [Insert your top 2-3 findings here, e.g. revenue concentration by segment]

## Segment Distribution
![Segments](images/segment_distribution.png)
