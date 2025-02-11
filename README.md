# House Pricing Data Analysis and Predictive Modeling

### Overview

This project is a complete end-to-end data analysis pipeline focused on understanding housing prices in Oeiras.
The workflow begins with web scraping, followed by data cleaning, exploratory analysis, and predictive modeling using a Linear Regression model.

## Workflow
- Data Collection – Scraped housing listings for Oeiras, extracting relevant fields such as size, number of rooms, and price.
- Data Cleaning & Preprocessing – Identified and handled outliers, missing values, and formatted data for analysis.
- Exploratory Data Analysis (EDA) – Examined distribution, trends, and correlations in the dataset.
- Modeling (Linear Regression) – Built a predictive model to analyze the relationship between housing characteristics and price.
- Multicollinearity Check (VIF Analysis) – Verified variable independence to improve model reliability.

## Main Conclusions (Summary)
- Living area and house type (Moradia) are the strongest predictors of price.
- Energy efficiency impacts price significantly. Higher-rated homes sell for more.
- Older properties tend to be slightly cheaper.
- No significant effect from floor level (after accounting for house vs. apartment)

## Limitations (Brainstorm)
- Location Impact – Comparing prices across different regions could provide deeper insights into the influence of geography.
- Limited Sample Size – A larger dataset would enhance model robustness and predictive accuracy.
- Feature Engineering – Additional variables like proximity to transport, neighborhood quality, could improve the model.

## Future Work Ideas
- Checking price changes overtime - Are prices significantly higher next year for a house with similar characteristics?
- Checking seasonality effects – Are prices higher at certain times of the year?
- Examining price per square meter instead of total price for a more comparable metric.


  
