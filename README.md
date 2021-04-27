# House-Prices-Advanced-Regression-Techniques

The aim for this project is to predict accurate Housing Prices using advanced regression techniques. This data is taken from kaggle and can be found [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## About 

Many problems in the industry can be solved using Regression. I have tried various models such as Linear Regression and advanced models such as Gradient Boosted Trees, Random Forest Regression and XGBoost to get the most accurate prediction of Housing Prices on the Ames Housing Dataset.

I have outlined the major steps in this project below:

1. Data Preprocessing and Exploration

* Deleting the huge outliners from data.
* Scaling transformation of target variable
* Feature Engineering for slection of better features for our data.
* There are many missing values in data so we will fill those values as given in the competition rules.
* Label Encoding some categorical variables
* Using Box Cox Transformation of (highly) skewed features

### Modelling

Importing all required libraries

Cross validation strategy definition

Base models used 

1.LASSO Regression

2.Elastic Net Regression

3.Kernel Ridge Regression

4.Gradient Boosting Regression

5.XGBoost

6.LightGBM 

### Stacking Models

Averaged base models class method

Ensembling StackedRegressor, XGBoost and LightGBM

Ensemble prediction and submission.





