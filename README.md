# car-price-prediction

## Problem Background and Motivation

In the automobile industry, pricing vehicles appropriately is crucial for competitiveness and profitability. This project aims to build a predictive model for car prices based on various vehicle features. By understanding the factors that influence car prices, the manufacturer can make informed decisions to optimize pricing strategies.

## Problem Statement

The project involves creating a price prediction model to understand how prices vary based on vehicle characteristics. The goal is to develop a model that accurately predicts the price of a vehicle given its features. This will enable senior leadership to gain insights into how different attributes impact pricing.

## Parameters/Features

The following features are considered to influence car prices:

1. Type of vehicle (e.g., Hatchback, Sedan, Coupe, Convertible)
2. Engine Capacity (Engine Power, Number of engine cylinders)
3. Vehicle style (Vehicle Size, Number of doors)
4. Transmission Type
5. Fuel Type
6. Drive Wheel
7. Engine Location
8. Mileage

## Agenda

1. Problem Background and Motivation
2. Import Package Dependencies
3. Custom Functions
4. Connect to Data Source and Data Extraction
5. Data Exploration and Transformation
6. Machine Learning Model
7. Conclusion
8. Appendix

## Import Package Dependencies

The project utilizes several libraries for data manipulation, visualization, and modeling:

- Pandas, Numpy, and Math: Data manipulation and mathematical operations
- Matplotlib, Seaborn, and Plotly: Data visualization
- SKLearn: Machine learning models and evaluation metrics
- Statsmodels: Statistical tests and data exploration

## Data Exploration and Transformation

The dataset undergoes a series of steps for exploration and transformation:

1. Initial Cleanup: Removing duplicates, handling missing values, and addressing data quality issues.
2. Outlier Detection & Treatment: Identifying and treating outliers in relevant columns.
3. Feature Creation: Creating new features based on existing data.
4. Feature Selection: Selecting relevant features based on their correlation with the target variable.
5. Feature Transformation: Encoding categorical variables, applying log-transform to the target variable, and rescaling numerical features.

## Machine Learning Model

Multiple models are built and evaluated to predict car prices:

1. Model 1: Using only Engine Horsepower as a predictor.
2. Model 2: Engine Horsepower and Vehicle Category (categorical) as predictors.
3. Model 3: Using a set of selected features for prediction.

The models' accuracy, 𝑅2, MAPE (Mean Absolute Percentage Error), and MSE (Mean Squared Error) are used to evaluate their performance. Model 3 achieves the highest accuracy and provides valuable insights into car price prediction.

## Conclusion

The project demonstrates how machine learning can be leveraged to predict car prices based on vehicle features. By understanding the influencing factors, the manufacturer can optimize pricing strategies and cater to various market segments effectively.

## Proposal for Next Steps

1. Validate the assumptions for linear regression, including linearity, endogeneity, normality, autocorrelation, and multicollinearity.
2. Deploy the predictive model on a webpage for user access.
3. Explore separate analysis for electric vehicles and analyze their pricing patterns.
4. Analyze manufacturing costs to ensure profitable pricing strategies.

## Communication to Business Leaders

The project's outcome provides actionable insights for pricing strategies in the automobile industry. By understanding the impact of various features on car prices, the manufacturer can optimize pricing and cater to different customer segments effectively. The predictive model helps senior leadership make informed decisions and set competitive prices.
