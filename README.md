# LITA_Customer_Project
# Customer Data 

## Overview

This repository contains a comprehensive analysis of customer data to track subscription trends, identify key customer segments, and analyze revenue streams. Using Excel for data preparation, SQL for data processing and querying, and Power BI for visualization, the project offers insights into key metrics such as customer subscriptions, cancellation trends, regional performance, and revenue analysis.

## Objectives
Customer Overview: Detailed customer profiles including Customer ID, Customer Name, and Region.
Subscription Analysis: Track the types of subscriptions and identify popular subscription types.
Revenue Insights: Analyze total and segmented revenue across different regions and subscription types.
Duration Calculation: Calculate subscription durations and identify long-term customers.
Cancellation Analysis: Track and analyze canceled subscriptions and the associated revenue impact.
Project Structure

- Data Collection and Preparation
Source: Customer data file with the following columns:
Customer ID: Unique identifier for each customer.
Customer Name: Full name of the customer.
Region: Geographical area of the customer.
Subscription Type: Type of subscription (e.g., Basic, Premium).
Subscription Start: Date when the subscription began.
Subscription End: Date when the subscription ended, if applicable.
Canceled: Status indicating whether a subscription was canceled.
Revenue: Revenue generated from each customer.
Data Cleaning: Data is cleaned in Excel to ensure accurate dates, fill missing values, and maintain consistent format.

3. SQL Analysis
Purpose: Perform data calculations and generate insights.
Queries:
Total Revenue by Region: Calculate total revenue segmented by region.
Subscription Duration: Calculate the duration between Subscription Start and Subscription End dates.
Cancellation Trends: Identify customers with canceled subscriptions and analyze their revenue impact.
Top Subscription Types: Find the most popular subscription types by customer count.
Key SQL Calculations:
DATEDIFF function to calculate Subscription Duration for each customer.
Summing Revenue for active and canceled subscriptions.

5. Power BI Dashboard
Dashboard Components:
Customer Overview: Display customer count by region and subscription type.
Revenue Analysis: Visualization of total revenue by region and subscription type.
Subscription Duration: Average duration analysis for each subscription type.
Cancellation Overview: Canceled subscriptions with associated revenue and trends.

Interactive Elements:
Slicers: Slicers for filtering by region, subscription type, and cancellation status for dynamic analysis.
Drill-Down: Drill-down options for subscription duration and customer-level revenue.

7. Key Insights
Revenue by Region: Regions generating the most revenue, enabling targeted strategies for high-value areas.
Subscription Duration: Insights into average subscription lengths, identifying potential for retention improvements.
Popular Subscription Types: Data on subscription preferences, highlighting types with the most active users.
Cancellation Impact: Revenue impact and patterns for cancellations, supporting customer retention initiatives.
Usage

Excel File: Open the file for preliminary data structure, cleaning, and data validation.
SQL Scripts: Run the SQL queries for specific customer insights and calculations.
Power BI Dashboard: Use the interactive dashboard for a comprehensive view and interactive filtering of customer data.

## Visualization On Power BI
![Screenshot (69)](https://github.com/user-attachments/assets/8e5eda10-c4ce-42a5-85f2-61585e23f418)

## Conclusion
The Customer Data Repository provides a powerful approach to understanding customer behavior and revenue patterns, 
enabling data-driven decisions for targeted marketing, customer retention, and subscription management.
