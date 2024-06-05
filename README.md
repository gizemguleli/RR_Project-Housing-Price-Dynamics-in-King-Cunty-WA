# RR_Project-Housing-Price-Dynamics-in-King-Cunty-WA
Enhancing reproducible research from Data Exploration to Advanced Analysis

## Project Summary

This project uses advanced data visualization techniques in Python to analyze house prices in King County, Washington. The dataset, obtained from Kaggle, provides 21,613 observations of 21 distinct variables over one year (May 2014 - May 2015). Link to the data: https://www.kaggle.com/datasets/shivachandel/kc-house-data/data

Objectives

The objective of this project is two-fold:

    Develop advanced visualizations that allow us to explore relationships between variables and understand patterns in house sales data.
    Identify and interpret factors that contribute to the variations in house values.

## Data Description

The dataset consists of both numerical and categorical variables, covering various aspects like the number of bedrooms, bathrooms, living space, lot size, etc. The geographical coverage is King County, including the city of Seattle.
**Variables**: 21 (id, date, price, bedrooms, bathrooms, sqft_living, sqft_lot, floors, waterfront, view, condition, grade, sqft_above, sqft_basement, yr_built, yr_renovated, zipcode, lat, long, sqft_living15, sqft_lot15)
**Observations**: 21,613
**Period**: 02 May 2014 to 27 May 2015
**Geographic coverage**: King County, including Seattle

## Prerequisites

- **Dataset**: either downloadable from this repository or directly from Kaggle
- **Python version**: 3.8+
- **Required packages**: pandas, matplotlib, seaborn, numpy, scipy, geopandas.
- This project was done using a Jupyter notebook, we recommend following the analysis with the file in this repository _V1.ipynb_ as it contains more details and conclusions of the project. The following sections will describe briefly what was done. If you are interested in further details, the code, and/or replicating our analysis, please follow the _V1.ipynb_ file.

## Exploratory Data Analysis (EDA)

Through the use of several Python packages, we will carry out thorough data exploration. This includes correlation analysis, distribution analysis, and other related techniques to help understand the underpinnings of our data.
Advanced Visualization Techniques

Our project uses scatter plot matrices, interactive visualizations, and custom plots to delve deeper into the data.

## Geospatial Visualization

Given that our dataset provides geographical coordinates, we will create maps to visualize the spatial distribution of house prices within King County and Seattle. The idea is to identify regional patterns and hotspots of high-value properties.

## Machine Learning Modeling

TBD...

## Conclusion

Overall, through advanced visualization techniques, this project aims to deliver valuable insights into the factors influencing house sales in King County, Washington. The blend of exploratory data analysis with visual representations will pave the way toward a comprehensive understanding of regional housing market dynamics.
