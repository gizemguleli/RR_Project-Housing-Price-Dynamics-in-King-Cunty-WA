# RR_Project-Housing-Price-Dynamics-in-King-Cunty-WA
Enhancing reproducible research from Data Exploration to Advanced Analysis

## Project Summary

This project we are using advanced data visualization techniques and machine learning modeling  in Python to analyze house prices in King County, Washington. 
The dataset, obtained from Kaggle, provides 21,613 observations of 21 distinct variables over one year (May 2014 - May 2015).
 Link to the data: https://www.kaggle.com/datasets/shivachandel/kc-house-data/data

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
- **Jupyter Notebook**: This project was conducted using a Jupyter notebook. We recommend following the analysis with the file in this repository named _V1.ipynb_. This notebook contains detailed explanations, code, and conclusions of the project.
- **Usage**: To replicate our analysis or further explore the dataset, simply open the _V1.ipynb_ file in a Jupyter Notebook environment and execute the cells sequentially. This notebook contains step-by-step instructions and code comments to guide you through the analysis process.


## Exploratory Data Analysis (EDA)

Through the use of several Python packages, we will carry out thorough data exploration. This includes correlation analysis, distribution analysis, and other related techniques to help understand the underpinnings of our data.
Advanced Visualization Techniques

Our project uses scatter plot matrices, interactive visualizations, and custom plots to delve deeper into the data.

## Advanced Visualization Techniques

Scatter plot matrices, interactive visualizations, and custom plots are utilized to gain deeper insights into the data.

## Machine Learning Modeling

In this phase of the project, we will develop and fine-tune machine learning models to predict house prices in King County, WA. This section will include the following steps:

1. **Data Preprocessing**: We will handle missing values, encode categorical variables, and scale numerical features as necessary.

2. **Feature Engineering**: Creating new features or transforming existing ones to improve model performance.

3. **Model Selection**: We will experiment with various regression algorithms such as Regression Trees , and Gradient Boosting Regression.

4. **Model Evaluation**: Using appropriate evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to assess model performance.

5. **Hyperparameter Tuning**: Fine-tuning the chosen model(s) to optimize performance.

6. **Prediction**: Making predictions on the test dataset and evaluating the model's performance on unseen data.

The detailed implementation and results of each step will be documented in the Jupyter notebook _V1.ipynb_ for further reference and reproducibility.


## Conclusion

Overall, through advanced visualization techniques, this project aims to deliver valuable insights into the factors influencing house sales in King County, Washington. The blend of exploratory data analysis with visual representations will pave the way toward a comprehensive understanding of regional housing market dynamics.
