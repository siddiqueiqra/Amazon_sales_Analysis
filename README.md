# Amazon Sales Data Analysis

## Problem Statement

In today's competitive business landscape, effective sales management has become crucial to minimize costs and maximize profits. Sales management plays a pivotal role in commercial enterprises, serving as the cornerstone of business success.

## Objectives

This analysis aims to achieve the following objectives:

- Optimize pricing strategies and discount offerings.
- Enhance inventory management processes.
- Execute precise customer segmentation.
- Forecast sales trends.
- Evaluate promotional campaigns.
- Streamline operational efficiency.
- Assess sales performance.
- Identify cross-selling and upselling opportunities.

## Approach

### Data Preparation

- Import the necessary Python libraries: Pandas, NumPy, Matplotlib, Seaborn.
- Load the sales dataset from an Excel file.

### Data Cleaning

- Begin by exploring the dataset's structure using `df.head()` and `df.shape`.
- Identify and handle missing values using `df.isna().sum()` and drop incomplete rows using `df.dropna()`.
- Adjust data types and convert categorical columns into categorical data types.

### Data Analysis

1. **Exploratory Data Analysis (EDA)**

   - Calculate essential metrics: Total Discount Amount, Total Sales Amount, Average Discount Percentage, Average Sales Margin, Average Sales Quantity, and Average Sales Price.
   - Perform correlation analysis between Discount Amount and Sales Amount, as well as between Discount Amount and Sales Margin Amount.
   - Visualize the relationships between Discount Amount and Sales Amount, and between Discount Amount and Sales Margin Amount.

2. **Time Series Analysis**

   - Set 'Invoice Date' as the index for time-based analysis.
   - Resample and plot monthly sales and discount trends.
   - Apply seasonal decomposition to unveil underlying trends, seasonality patterns, and residuals.

3. **Customer Segmentation**

   - Compute Recency, Frequency, and Monetary metrics.
   - Standardize the metrics using StandardScaler for meaningful comparisons.
   - Employ K-Means clustering to categorize customers into low value, high value, and median value clusters.
   - Assign cluster labels to customers and analyze their distribution.

### Conclusion

This Amazon Sales Data Analysis has illuminated key insights and strategies:

- Optimization of pricing and discounts.
- Enhancement of inventory management.
- Precision in customer segmentation.
- Recognition of sales trends through time series analysis.
- Evaluation of customer behaviors, discount efficacy, and sales margin influence.
- Identification of seasonal patterns for strategic planning.
- Personalized marketing strategies enabled by customer segmentation.

These findings offer invaluable guidance for strategic decision-making, empowering Amazon to amplify sales, trim costs, and augment profits within its sales ecosystem.
