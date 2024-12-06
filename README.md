# Stock Price Analysis

This project focuses on analyzing stock price trends and behavior using Python. It utilizes historical stock data to perform various analyses and visualize key insights, enabling a better understanding of stock performance over time.

## Overview

The notebook includes:
1. **Data Collection**:
   - Reads stock price data for multiple companies (e.g., Apple, Amazon, Google, Microsoft) over five years.
   - Extracts and processes CSV datasets.

2. **Time-Series Analysis**:
   - Examines the change in stock prices over time.
   - Calculates and visualizes moving averages for various stocks.

3. **Daily Stock Return Analysis**:
   - Analyzes daily changes in stock prices.
   - Formula for daily stock return:
     \[
     \text{Daily Return} = \text{Closing Price} - \text{Opening Price}
     \]

4. **Resampling Analysis**:
   - Aggregates and analyzes stock price data at different intervals (e.g., weekly, monthly).
   - Identifies trends and patterns in stock price behavior.

## Features

- **Visualization**:
  - Uses Matplotlib and Seaborn for graphical representation of trends.
  - Includes line plots for moving averages and other price metrics.

- **Data Handling**:
  - Processes datasets for multiple companies.
  - Applies resampling techniques for interval-based trend analysis.

## Libraries Used

- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization
- `glob` for handling file paths

## Results

- Moving averages provide insights into long-term trends for selected stocks.
- Daily stock return analysis reveals patterns in short-term price fluctuations.
- Resampling identifies seasonality and periodic trends in stock behavior.
