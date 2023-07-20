# House Prices 

## Overview

This repository contains the analysis of the "House Prices - Advanced Regression Techniques" dataset from Kaggle. The goal of the project is to predict the sale price of houses in Ames, Iowa. The dataset includes a variety of explanatory variables describing various aspects of residential homes.

## Methodology

The methodology followed in this repository consists of the following steps:

1. Data Cleaning and Preprocessing: This involved handling missing data, transforming variables as needed, and ensuring that the data was appropriately prepared for the subsequent analysis.
2. Feature Selection: An initial feature selection process was conducted, but it was eventually decided to use all the features in the dataset.
3. Model Selection and Hyperparameter Tuning: Two primary models were selected: XGBoost and Random Forest. A grid search was performed to identify the optimal hyperparameters for each model.
4. Model Ensembling: An ensemble model was created that combines the XGBoost and Random Forest models, using a linear regression model as the meta-model. This approach aims to take advantage of the strengths of each model, to make a more robust overall prediction.
  
## Dependencies

This project uses the following dependencies:

Python

Pandas

Numpy

Scikit-learn

XGBoost

Matplotlib

## Acknowledgments

Thanks to Kaggle for providing the House Prices - Advanced Regression Techniques dataset.

Thanks to the open source community for the various tools and libraries that made this project possible.


