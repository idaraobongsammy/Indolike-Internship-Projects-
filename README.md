
Customer Analytics Portfolio
🚀 Project Overview
This repository showcases two distinct data analysis projects performed on large datasets to derive actionable insights for e-commerce and retail operations. The analyses focus on understanding customer satisfaction and identifying core sales trends and anomalies.
Project
Focus Area
Key Tool
Summary
Customer Sentiment Analysis
Customer Feedback & Product Ratings
Python (Pandas)
Categorized millions of product ratings into Positive, Neutral, and Negative sentiments to measure overall customer satisfaction.
Sales Trend Analysis
Time-Series Forecasting & Anomaly Detection
Python (Time Series)
Identified yearly growth, seasonal patterns (monthly/quarterly), and statistical anomalies in sales data to optimize business planning.

🧭 Repository Structure
The projects are organized into separate, self-contained directories, with the full report available as the README.md within each folder.
/Data-Analysis-Projects/
├── README.md                 <-- (You are here) Main Index
├── 01_Customer_Sentiment/    <-- Detailed Sentiment Analysis Project
└── 02_Sales_Trend_Analysis/  <-- Detailed Sales Trend Project


1️⃣ Customer Sentiment Analysis
This project analyzed over 7.8 million customer ratings to categorize feedback into clear sentiment classes (Positive, Neutral, Negative).
Key Findings Snapshot
Overall Sentiment: 55.56% of reviews were classified as Positive.
Data Size: 7,824,481 reviews analyzed.
Goal: Provide a quantitative measure of customer satisfaction based on rating scores (1-5 stars).
➡️ View Full Customer Sentiment Report
2️⃣ Sales Trend Analysis
This project performed time-series decomposition to analyze sales patterns across a four-year period, focusing on seasonal peaks and statistical outliers.
Key Findings Snapshot
Overall Trend: Consistent progressive sales growth year-over-year.
Peak Season: Q4 (October-December) consistently drives the highest sales.
Anomalies Detected: November and December were identified as statistically significant sales outliers (Z-score > 1.5).
Actionable Insight: Optimize marketing and inventory around end-of-year holidays and strong performance days (Monday and Friday).
➡️ View Full Sales Trend Report
🛠️ Tools Used
Tool
Purpose
Python
Core language for analysis and scripting.
Pandas
Data loading, cleaning, and aggregation.
Jupyter Notebooks
Reproducible analysis and iterative coding.
Z-score
Statistical method used for anomaly detection in sales data.
Markdown
Report generation and documentation.


