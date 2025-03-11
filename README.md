# Portfolio Analysis Challenge

This challenge is designed to test your skills in portfolio analysis using Python. Portfolio analysis involves evaluating investment portfolios to optimize asset allocation and management through various financial metrics and visualizations.

## Overview

- **Objective**: Perform calculations and create visualizations to analyze a set of financial assets.
- **Skills Demonstrated**: Python programming, data analysis, financial metrics calculation, and data visualization.

## Part 1: Data Loading and Price Charting

### Tasks:
1. **Data Loading**: Load the file `asset_price_data.csv` containing pricing information for various financial assets.
2. **Visualization**: Create a time series graph to visualize the asset price data. Ensure all asset price series begin at a uniform value to maintain the integrity of the analysis.

## Part 2: Daily Percentage Returns

### Tasks:
1. **Calculate Daily Percentage Returns**: Compute the daily percentage returns for each financial asset.
2. **Correlation Matrix**: Calculate the correlation matrix for the five assets.
3. **Scatter Plot**: Create a scatter plot comparing the returns of two specific assets.

## Part 3: Portfolio Analysis

### Tasks:
1. **Data Loading**: Load the file `portfolio_weights.csv` containing the daily weights of each asset in the portfolio.
2. **Visualization**:
   - Create an area chart of the asset weights.
   - Plot the historical cumulative returns of the portfolio.
3. **Performance Metrics**:
   - Calculate the annualized return of the portfolio.
   - Determine the annualized volatility of the portfolio (using an annualization factor of 261 days).
4. **Categorized Asset Weights**:
   - **Step 1**: Merge `portfolio_weights` with `asset_information` to get asset categories. Assign the result to `portfolio_weights_categories`.
   - **Step 2**: Group `portfolio_weights_with_categories` by each `Family` category. Then sum over each category to get asset weights by their categories. Assign the result to `grouped_weights`.
   - Create an area chart grouping asset weights by their categories.

## Summary

This challenge requires a combination of data loading, manipulation, visualization, and financial metric calculation. The tasks are designed to simulate real-world portfolio analysis, providing a comprehensive test of your Python and financial analysis skills.