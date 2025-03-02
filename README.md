# Data-Analysis-of-Fine-Food-Review

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : PUTUL SAINI

*INTERN ID* : CT6WNOD

*DOMAIN* : Data Analyst

*DURATION* : 6 WEEKS

*MENTOR* : NEELA SANTOSH

Dataset link : https://www.kaggle.com/code/mojganb/amazon-fine-food-lstm/input

📌 Objective of the Amazon Fine Food Review Analysis Project

* The main objective of this project is to analyze customer reviews of food products on Amazon to gain actionable insights for business decision-making.

# **Project Overview**

The Amazon Fine Food Reviews Dataset is a comprehensive collection of customer reviews on food products sold on Amazon. This project focuses on analyzing customer sentiment, review trends, and product performance using Power BI.

By leveraging data visualization, DAX measures, and AI-powered insights, the dashboard provides valuable information for business decision-making, helping companies enhance customer satisfaction and optimize product offerings.


## Key Insights from the Dashboard

🔹 1. Review Growth Trends Over Time

✅ The Total Number of Reviews increased by an impressive 3,55,082.14% between October 1999 and October 2012, showing a significant rise in customer engagement.

✅ A notable surge in reviews started in January 2010, with a 235.53% increase (943,409 reviews) in just 10 quarters.

🔍 Business Insight:

The sharp increase in reviews suggests a growing customer base and higher engagement.

The company should analyze what changed in 2010 (marketing, product launches, or promotions) to replicate the success.

🔹 2. Average Rating Decline

✅ The Average Rating dropped from 4.48 to 4.03 between July 2005 and October 2012, marking the steepest decline in product satisfaction.

🔍 Business Insight:

A declining rating trend suggests deteriorating product quality, customer dissatisfaction, or misleading product expectations.

The company should investigate top complaints in negative reviews and improve customer feedback mechanisms.

🔹 3. Top Reviewed Products

✅ The most reviewed product is B006MONQMC with 21,320 reviews, followed by B002LANN56 and B001VJ0B0I.

✅ B006MONQMC alone accounts for 21.94% of all reviews, indicating high popularity.

🔍 Business Insight:

Popular products should be prioritized for promotions and marketing campaigns.

Investigate why these products have high review counts – Are they best sellers or controversial products?

📌 Project Steps: How This Dashboard Was Created

Step 1: Data Collection & Preparation

* The dataset was imported from Amazon Fine Food Reviews (CSV file).
* The data was cleaned in Power Query:
  * Removed duplicates & missing values.
  * Converted Unix timestamps to Date format.
  * Extracted text length and helpfulness ratios.
 
Step 2: Data Modeling & Relationships

* Relationships were created between:
* ProductId ↔ Review Data
* Review Score ↔ Sentiment Analysis
  
Step 3: DAX Measures & KPIs

* Total Reviews → COUNT(Reviews[Id])
* Average Rating → AVERAGE(Reviews[Score])
* Positive Review % → Reviews with 4+ star ratings
* Negative Review % → Reviews with ≤2-star ratings
* Most Reviewed Product → Using TOPN() to find the product with highest review count
  
Step 4: Data Visualization in Power BI
✅ Key Visuals Used in the Dashboard:

Visualization	Purpose:

* KPI Cards -	Show Total Reviews, Average Rating, Sentiment %
* Bar Chart -	Display Top Reviewed Products
* Line Chart -Review Trends Over Time
* Pie Chart	 -Sentiment Analysis (Positive vs. Negative)

📌 Final Outcome

This Amazon Fine Food Review Dashboard provides valuable insights into customer behavior, product performance, and sentiment analysis. With interactive filters, AI-powered insights, and trend visualizations, this dashboard helps businesses make data-driven decisions to improve customer satisfaction and optimize product strategies.

📌 Final Goal

This project helps businesses make data-driven decisions by analyzing real customer feedback. The insights can be used to:

🚀 Improve product quality and customer engagement.
🚀 Optimize marketing & pricing strategies based on review trends.
🚀 Enhance customer trust by addressing key pain points.







