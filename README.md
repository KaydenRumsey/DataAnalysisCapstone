# Real Estate Price Prediction

This project is part of my data analytics capstone. It explores a large global real estate dataset to identify patterns in housing prices and builds a predictive model to estimate apartment values based on key features.

## Project Overview

I worked with a dataset of apartment listings containing over 140,000 records from around the world. The goal was to simulate a real-world analytics problem—cleaning and preparing raw data, uncovering meaningful trends, and developing a machine learning model to predict housing prices.

## Dataset Information

**Source:** [Kaggle - World's Real Estate Data](https://www.kaggle.com/datasets/toriqulstu/worlds-real-estate-data147k) 
**Format:** Excel (.xlsx)

**Content Overview:**

- **Country**: The country where the property is located  
- **City**: City of the listed property (when available)  
- **Price in USD**: Listed price of the apartment, converted to U.S. dollars  
- **Building Construction Year**: Year the building was constructed  
- **Building Total Floors**: Total number of floors in the building  
- **Apartment Floor**: Floor level of the apartment unit  
- **Apartment Rooms**: Total number of rooms  
- **Apartment Bedrooms**: Number of designated bedrooms  
- **Apartment Bathrooms**: Number of bathrooms  
- **Apartment Total Area**: Total size of the apartment in square meters  
- **Apartment Living Area**: Size of the main living space in square meters  

This dataset was chosen for its size, geographic diversity, and relevance to real-world housing market analysis.


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

## How to Run This Project

You can run this notebook in Google Colab

### Google Colab 
1. Go to [Google Colab](https://colab.research.google.com/)
2. Click **"File" > "Open notebook"**
3. Choose the **GitHub** tab
4. Paste this repo URL: `https://github.com/KaydenRumsey/DataAnalysisCapstone`
5. Select the notebook file: `KaydenRumseyCapstonePolished.ipynb`
6. Make sure to upload the dataset (`WorldRealEstateData.xlsx`) when prompted or manually
