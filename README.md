# Customer-Segmentation-using-RFM-Analysis

This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis on a retail dataset.
The goal is to identify high-value customers, loyal customers, and customers at risk of churn so that businesses can make better marketing and retention decisions.
##Business Objective
Companies need to understand customer behavior to:
Increase customer retention
Improve targeted marketing campaigns
Identify high-value customers
Reduce churn
RFM analysis helps segment customers based on their purchase patterns.
##Dataset
The dataset contains transactional data from an online retail store, including:
Customer ID
Invoice number
Invoice date
Product quantity
Unit price
From this data, we calculate:
Recency: Days since last purchase
Frequency: Number of purchases
Monetary: Total spending
##Tools & Technologies
Python
Pandas
Matplotlib
Jupyter Notebook
##Project Workflow
1. Data Cleaning
Standardized column names
Removed missing customer IDs
Removed negative or zero quantities
Converted date columns to datetime format
2. Feature Engineering
Created Total Sales column:
Total Sales = Quantity × Price
3. RFM Calculation
Grouped data by customer and calculated:
Recency
Frequency
Monetary value
4. RFM Scoring
Customers were scored from 1 to 4 using quartiles:
Higher R score = more recent purchase
Higher F score = more frequent purchases
Higher M score = higher spending
Combined to create an RFM score.
5. Customer Segmentation
Customers were categorized into business segments:
Champions
Loyal Customers
Potential Loyalists
New Customers
At Risk
Lost Customers
Visualizations
The project includes:
Customer count by segment
Average revenue by segment
These visualizations help identify which segments are most valuable.
##Key Insights
Champions generate the highest revenue.
Loyal customers provide stable income.
At-risk customers show declining activity.
Lost customers have low engagement.
##Business Recommendations
Reward champions with loyalty programs.
Offer targeted promotions to at-risk customers.
Re-engage lost customers with special discounts.
Convert potential loyalists into long-term customers.
