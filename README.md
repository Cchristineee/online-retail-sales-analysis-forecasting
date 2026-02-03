# Online Retail Sales Analysis & Forecasting (UK)

## Overview
This project analyzes over 500,000 online retail transactions to uncover sales trends, customer purchasing behavior, and top-performing products in the United Kingdom market. The analysis concludes with a time-series forecasting model to estimate future monthly revenue.

## Business Questions
- Which products generate the most revenue?
- When do customers buy the most (seasonality, weekdays, hours)?
- What are expected future sales trends?

## Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Time Series Forecasting (Exponential Smoothing)
- Jupyter Notebook

## Key Insights
- Strong seasonality with peak sales in November and December
- Revenue concentrated during weekdays and business hours
- Decorative and seasonal products dominate top revenue rankings
- Shipping charges represent a significant revenue component

## Forecasting
A seasonal exponential smoothing model was used to forecast monthly revenue, capturing trend and yearly seasonality. Forecasts suggest continued late-year peaks and early-year slowdowns.

Forecasts are directional due to limited historical depth; future work includes multi-year seasonal modeling and product-level demand forecasting.

## Files
- `Online_Retail_Analysis.ipynb`: Full analysis and forecasting workflow
- Dataset source: https://www.kaggle.com/datasets/vijayuv/onlineretail

## Future Improvements
- Product-level demand forecasting
- Multi-year time series modeling
- Customer segmentation and clustering
