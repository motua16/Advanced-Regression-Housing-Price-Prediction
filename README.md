# House-Prices-Advanced-Regression-Techniques

The aim for this project is to predict accurate Housing Prices using advanced regression techniques. This data is taken from kaggle and can be found [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## About 

Many problems in the industry can be solved using Regression. I have tried various models such as Linear Regression and advanced models such as Gradient Boosted Trees, Random Forest Regression and XGBoost to get the most accurate prediction of Housing Prices on the Ames Housing Dataset.

I have outlined the major steps in this project below:

`1.` Data Preprocessing and Exploration

* Importing all required libraries
* Deleting the huge outliners from data.
* Scaling transformation of target variable
* Feature Engineering for slection of better features for our data.
* There are many missing values in data so we will fill those values as given in the competition rules.
* Label Encoding some categorical variables
* Using Box Cox Transformation of (highly) skewed features

`2.` Modelling and generating Predictions

* Models used are listed below :

  * LASSO 
  * Linear Regression
  * Gradient Boosting Regression
  * XGBoost

* Generating prediction and submission.

## Input Data

The dataset contains 81 columns and there are 1460 data points for training and 1459 data points to predict for. A description of all columns is given below :

Description of all the columns can be found [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

## Repository Structure and Description

`
| - data
| |- train.csv # training data
| |- test.csv # test data
`
- README.md
- housing-prediction.ipynb # Python 3 notebook, which depicts the working
- submission.csv # submission generated from this notebook

## Improvements

The following improvements can be made over this:

* Engineering new features from the given columns
* Trying other models such as Light-GBM






