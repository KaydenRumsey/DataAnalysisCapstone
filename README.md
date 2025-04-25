# Real Estate Price Prediction

This project is part of my data analytics capstone. It explores a large global real estate dataset to identify patterns in housing prices and builds a predictive model to estimate apartment values based on key features.

## Project Overview

I worked with a dataset of apartment listings containing over 140,000 records from around the world. The goal was to simulate a real-world analytics problem—cleaning and preparing raw data, uncovering meaningful trends, and developing a machine learning model to predict housing prices.

## Business Problem

Property prices are influenced by a wide range of variables, such as square footage, number of rooms, and the age of the building. This project aims to answer:

- What features have the strongest impact on price?
- Can we use these features to accurately predict the value of a property?

A solution like this could help real estate professionals and investors make faster, more informed decisions.

## Dataset and Cleaning

The dataset included features such as:

- Apartment size and living area
- Number of rooms, bedrooms, and bathrooms
- Construction year and floor information
- Listed price in USD

Key cleaning steps included:
- Removing nulls in essential fields
- Converting area values to numeric format
- Replacing missing values with medians
- Removing outliers using the IQR method

## Analysis and Modeling

After cleaning the data, I explored feature distributions and correlations using visualizations. I then trained a Random Forest regression model using features like:

- Apartment total and living area
- Number of rooms and bathrooms
- Building age
- Apartment floor ratio

Model performance was evaluated using R² and RMSE scores. Feature importance metrics were also visualized to understand which inputs had the greatest influence on price.

## Key Insights

- Apartment size was the strongest predictor of price
- Number of rooms and bathrooms significantly influenced value
- Older buildings tended to have lower prices
- Even without detailed location data, the model produced reasonably accurate price estimates

## Conclusion

This project demonstrates a complete data analytics workflow:
- Cleaning and preparing raw data
- Exploring patterns with visual analysis
- Building and evaluating a machine learning model

With further enhancements, such as incorporating geographic data or interactive dashboards, this work could be developed into a full real estate pricing tool.

## How to Use

Clone the repo or download the notebook file and run it in Jupyter Notebook or Google Colab. All steps are labeled and documented for ease of navigation.
