# House-Prices-Advanced-Regression-Techniques

This data is taken from kaggle.

### Data Processing

Deleting the huge outliners from data.
  
Log - transformation of target variable

Feature Engineering for slection of better features for our data.

Data Correlation matrix for viwing the relationship of variables.

There are many missing values in data so we will fill those values as given in the competition rules.

Label Encoding some categorical variables

Using Box Cox Transformation of (highly) skewed features

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





