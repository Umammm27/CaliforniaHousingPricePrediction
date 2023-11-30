# **California Housing Price Prediction using GradientBoost-Regressor Model**
# About
This project is a part of JCDS Program : Purwadhika. This Repository contains file Python Notebook and file .sav (for model machine learning) for my Analyze about this Case Study. This project contains the results of my prediction using machine learning for California Housing Price. The data contains information from the 1990 California census about house value based on various attributes.

# Business Task
Housing is one of the essential needs for every family, but knowing the price of a house according to the value and conditions offered is usually a challenge that is quite confusing for them, as is also the case for developers or property developers who build houses in an area. They can at least make decisions based on historical data of previous home prices in the area to determine the right price for their property.

The California Housing Price dataset is a data collection that includes information about house prices in various regions in California, USA in 1990 which has more than 50 regions with variations in property prices. This data not only includes house prices, but also various supporting conditions and demographics that influence property values. Analysis of this dataset can provide insight into what factors have the greatest influence on home prices in different areas of California. Predictive models can be developed to predict home prices based on a combination of every available variable. This can give potential property buyers or investors a better view of the factors that influence property prices in California.

# Business Problem
A property development company should be able to provide and build houses that are not only competitive in price in each area, but also provide optimal value. This will of course enable the property to be sold quickly while increasing profits for the company.

# Project Workflow
1. Data Preprocessing
2. Feature Engineering
3. Splitting Data
4. Model Benchmarking
5. HyperParameter Tunning
6. Predicted using Best Model
7. Predicted on Data Holdout
8. Model Evaluation
   
# Result and Conclusion
1. Best Model: GradientBoost-R
2. Best Params: learning rate: 0.1 | alpha: 0.1 | max_depth: 7 | n_estimators: 300
3. Metrics Evaluation: Med-AE
4. Test-Scoring (Med-AE) : 19706 | (MAPE): 0.18
5. Feature Importances: median_income, location, population per household.

# Data Source
https://www.kaggle.com/datasets/camnugent/california-housing-prices

# Note: 
If you want to use the model I have created, follow these instructions:
1. Carry out the process of adding a new column: `population per household` which is based on the `population` column divided by the `household` column.
2. Carry out the encoding process on the `ocean_proximity` column and delete one of the columns, namely the `ocean_proximity_ISLAND` column.
3. Carry out the binning process on the `housing_median_age` column and save the binning result label column to `house_age` and carry out the encoding process ordinally by determining the order according to the binning labels. for example: 1-10 is changed to 1, 11-20 is changed to 2, etc.

Status Project: **Completed**
