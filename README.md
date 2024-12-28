# Overview
## NYK-Taxi-Data-Analysis:Unlocking Insights from Urban Mobility
This project focuses on analyzing NYK Yellow Taxi trip data to provide actionable insights into fleet management and demand prediction. Using a subset of the NYC taxi dataset, the analysis emphasizes peak hour demand patterns, identifies high-trip-density neighborhoods, and explores potential optimizations for reducing passenger wait times.

# Resources

## Dataset Source: NYC Taxi and Limousine Commission Trip Data

## Data Dictionary: NYC Yellow Taxi Data Dictionary

## Industry Reports: TLC Industry Reports

# Dataset Details

The dataset includes taxi trip records spanning the following time periods in 2016:

2016-01-03 [00:00:00 - 23:59:00] (Tuesday)

2016-02-03 [00:00:00 - 06:14:00] (Wednesday)

2016-10-03 [07:08:00 - 18:32:00] (Thursday)

2016-11-03 [00:00:00 - 14:19:00] (Friday)

Each row in the dataset represents a single taxi trip with attributes such as pickup/dropoff location, fare, distance, and timestamps.

# Project Objectives

## Demand Prediction:

Analyze temporal patterns to predict peak demand hours.

Identify neighborhoods with high trip densities.

## Fleet Management:

Optimize resource allocation during peak hours.

Minimize passenger wait times by recommending optimal pickup points.

# Insights for Service Optimization:

Provide actionable recommendations for improving the taxi service experience.

# Methodology

# Exploratory Data Analysis (EDA):

Clean and preprocess the data to handle missing, invalid, or anomalous values.

Conduct descriptive analysis to understand trip characteristics and trends.

# Data Cleaning:

Removed invalid pickup/dropoff coordinates (e.g., 900+ invalid locations).

Filtered out trips with negative or zero distances (600+ records).

# Regression Analysis:

Used Ordinary Least Squares (OLS) regression to model demand patterns.

Achieved an Adjusted R-squared value of 0.848, indicating strong model performance.

# Key Findings:

## Peak Demand Hours: 8:00–10:00 AM and 5:00–8:00 PM.

## High-Density Areas: Five key neighborhoods with the highest trip volumes were identified.
