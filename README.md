Retail Customer Analytics & Churn Intelligence
Project Overview

This project focuses on analyzing retail transaction data to understand customer behavior, sales performance, churn risk, and revenue impact. The goal is to help businesses identify high-risk customers, prioritize retention efforts, and make data-driven decisions using analytics and machine learning.

Business Problem

Retail businesses often struggle to:

Identify valuable customers

Detect early signs of customer churn

Understand which segments generate or risk losing revenue

Decide where to focus retention efforts

This project solves these problems using structured data analysis and churn intelligence.

Data Source

Retail transaction dataset (invoices, products, customers, dates, quantities, prices)

Data loaded using Python and stored in a MySQL database for analysis

Key Steps Performed
1. Data Cleaning & Preparation

Removed invalid and negative quantities

Handled missing customer IDs

Created total transaction amount

Converted dates into usable time-based features

Ensured clean and consistent data before analysis

2. SQL Integration

Stored cleaned and transformed data in MySQL

Created analytical tables for customer-level insights

Used SQL for structured querying and validation

Core Analytics Performed
Sales & Revenue Analysis

Monthly sales trend analysis

Top-selling products by quantity and revenue

Country-wise revenue aggregation

Customer Analytics

RFM Analysis (Recency, Frequency, Monetary)

Automated RFM scoring (1–5 scale)

Customer segmentation based on RFM scores

Cohort Analysis

Grouped customers by first purchase month

Analyzed customer retention behavior over time

Market Basket Analysis

Applied Association Rule Mining (Apriori)

Identified frequently purchased product combinations

Extracted rules using support, confidence, and lift

Risk & Retention Intelligence
Churn Risk Scoring

Rule-based churn logic using recency and behavior

Classified customers into High, Medium, and Low risk

Revenue at Risk

Calculated potential revenue loss from high-risk customers

Customer Priority Score

Combined churn risk and monetary value

Ranked customers by business importance

Machine Learning (Churn Model)

Built a binary churn prediction model

Trained and evaluated using classification metrics

Generated churn probabilities for each customer

Applied probability calibration for realistic risk scoring

Advanced Decision Logic
Rule-Based vs ML Churn Comparison

Compared traditional business rules with ML predictions

Identified agreement and disagreement cases

Decision Threshold Optimization

Tuned churn probability thresholds for better business decisions

Action Recommendation Engine

Assigned actions such as:

Immediate Retention Call

Personalized Discount

Engagement Email

No Action Needed

Based on churn probability and customer priority

Technologies Used

Python (pandas, numpy, scikit-learn, mlxtend)

SQL / MySQL

Machine Learning (classification, calibration)

Jupyter Notebook

Final Outputs

Cleaned and structured SQL database

Customer segmentation and churn intelligence tables

Revenue-at-risk and priority scoring

Actionable insights for retention strategy

Project Value

This project demonstrates how data analytics and machine learning can be used together to:

Reduce customer churn

Protect revenue

Support business decision-making with clear, explainable insights

Future Improvements

Real-time data integration

Model retraining with new data

A/B testing of retention actions

Advanced customer lifetime value (CLV) modeling
