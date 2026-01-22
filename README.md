# Megaline Plan Revenue Analysis

## Overview
This project analyzes customer behavior and revenue generation for a telecommunications company offering two prepaid plans: Surf and Ultimate.  
The objective is to evaluate usage patterns, revenue stability, and overall profitability in order to support business decision-making.

## Dataset
The dataset contains information about:
- Users and their subscribed plans
- Call usage (minutes)
- Message usage
- Internet data consumption
- Monthly billing rules and overage charges

All analyses are based on a sample of 500 customers over the year 2018.

## Project Workflow
- Data cleaning and preprocessing
- Conversion and handling of date-related features
- Monthly aggregation of usage per user
- Revenue calculation based on plan pricing rules
- Exploratory Data Analysis (EDA)
- Statistical hypothesis testing
- Business-oriented conclusions

## Key Insights
- Users of both plans show similar behavior in calls and messages, with right-skewed distributions and heavy users in both groups.
- Internet usage is slightly higher on average for Ultimate users, while Surf users more frequently exceed included limits.
- The Ultimate plan generates higher and more stable average monthly revenue.
- The Surf plan shows higher revenue variability due to overage charges.
- Statistical tests confirm a significant difference in average revenue between the two plans.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy

## Notes
This project was developed as part of a data analytics bootcamp and later refined as a portfolio project.  
It demonstrates end-to-end analysis, from raw data preparation to statistical validation and business interpretation.
