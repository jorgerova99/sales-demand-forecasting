# Sales Demand Forecasting

## Business Problem
Accurately forecasting product demand is critical to optimize inventory levels, reduce costs, and improve customer satisfaction.

## Objective
Build a data-driven model to forecast future sales and provide actionable business insights.

## Tools
- Python
- pandas
- numpy
- matplotlib
- scikit-learn
## Exploratory Data Analysis (EDA)

The dataset contains 9,800 sales records with 18 features related to orders, customers, products, and dates.

### Data Cleaning
- Date columns (`Order Date` and `Ship Date`) were converted to datetime format.
- Only 11 missing values were found in the `Postal Code` column, which was not critical for the sales forecasting task.

### Time Series Analysis
- Daily sales were aggregated into monthly sales to reduce noise and better identify patterns.
- The monthly sales time series shows a clear upward trend over time, indicating business growth.
- Higher sales peaks are observed toward the end of each year, suggesting seasonal effects typical of retail businesses.

### Key Insights
- Sales variability is high at the daily level, making monthly aggregation more suitable for forecasting.
- The strongest sales performance occurs in the later years of the dataset, particularly in 2019.
- Time-based features such as year and month are relevant predictors for future sales forecasting models.
