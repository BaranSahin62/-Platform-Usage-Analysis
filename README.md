# Digital Banking Platform Analysis

## Overview

This project analyzes customer interactions across various digital banking platforms, including Mobile Banking, Internet Banking, and ATMs. It aims to extract insights into customer behavior, transaction types, platform transitions, and usage trends to enhance the overall banking experience.

## Objectives

- **Segment Customer Usage**: Classify customers based on their transaction frequency.
- **Analyze Transaction Types**: Assess the distribution of transaction types across platforms.
- **Identify Platform Transition Trends**: Examine how customers move between platforms.
- **Perform Time Series Analysis**: Track platform usage over time to identify patterns.

## Data Sources

The analysis relies on two main tables:
1. **customer_profiles**: Contains customer demographic data.
2. **platform_usage_logs**: Records transaction details for each customer, including platform used, transaction amount, duration, and date.

## SQL Queries

This project includes several SQL queries for different analyses:

### 1. Usage Intensity Segmentation

Segments customers into High, Medium, and Low usage based on transaction counts and calculates average transaction duration.

### 2. Transaction Type Distribution by Platform

Counts transactions and calculates total amounts and average durations for each transaction type across platforms.

### 3. Platform Transition Trends

Identifies trends in customer transitions between platforms, ensuring platform names are standardized.

### 4. Time Series Analysis

Analyzes transaction counts over time, categorizing data by month and platform.


