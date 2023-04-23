# Insurance Claims Severity Prediction Model

This project involves developing a machine learning model to predict the severity of insurance claims for Allstate, a personal insurer in the United States. The goal is to automate the prediction of claim costs and severity to improve the claims service for their customers.

## Data Overview

The dataset used in this project is provided by Allstate and contains information about insurance claims. The data includes various features such as policy holder information, vehicle information, and claim information. The target variable is the severity of the claim, which is measured by the amount of loss incurred by Allstate.

## Data Source

The dataset used in this project was sourced from the Allstate Claims Severity competition on Kaggle, which can be found at the following link:

[https://www.kaggle.com/competitions/allstate-claims-severity/data](https://www.kaggle.com/competitions/allstate-claims-severity/data)


The data includes various features such as policy holder information, vehicle information, and claim information, and is used to predict the severity of insurance claims for Allstate. 


## Methodology
An ensemble approach was used to develop the prediction model. The ensemble model consisted of **gradient boosting machine (GBM)**, **random forest regressor**, and **decision trees** algorithms. The hyperparameters of the ensemble models were tuned using **RandomizedSearchCV** to optimize the model's performance with minimized Root Mean Square Error (RMSE).

## Usage
The code for this project can be found in the `insurance-claims-prediction.ipynb` notebook. The notebook contains the data preprocessing steps, the model training, and the prediction of the test set. The `requirements.txt` file contains the necessary dependencies to run the notebook.

## Results
The developed prediction model was able to accurately predict the severity of the claims, and the RMSE was minimized using the optimized hyperparameters obtained through RandomizedSearchCV.

## Future Work
This project can be further improved by exploring other ensemble algorithms and performing feature engineering to identify important features for the prediction model. Additionally, the model can be deployed as an API to allow Allstate to automate the prediction of insurance claim severity.
