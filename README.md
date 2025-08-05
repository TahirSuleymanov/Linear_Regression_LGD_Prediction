# LGD Prediction using Linear Regression

This project demonstrates the development and deployment of a machine learning model for predicting Loss Given Default (LGD) using Linear Regression. The model is built and applied within the financial credit risk domain using structured data.

## Overview

The goal of the project is to estimate the LGD percentage for credit exposures based on a variety of borrower and loan characteristics. The entire process—from preprocessing the data to model deployment—is implemented within a single Jupyter Notebook.

## Key Steps in the Notebook

### 1. Data Preprocessing and Model Training

- **Exploratory data analysis** to understand the structure, distribution, and potential issues (e.g., multicollinearity) in the dataset  
- **Feature engineering**, including the creation of new variables such as region-wise average income and credit score-level average default history  
- **Univariate analysis** to reduce irrelevant or highly correlated features before training  
- **Encoding categorical variables** using One-Hot Encoding  
- **Scaling numerical features** for model compatibility  
- **Training a Linear Regression model** to predict LGD values  
- **Evaluating model performance** using metrics like R², RMSE, and MAE  

### 2. Prediction and Deployment

- **Inputting new data** to generate predictions using the trained model  
- **Preprocessing the new input data** using the same steps applied during training  
- **Generating LGD predictions** on the new (deployment) dataset  
- **Exporting the predictions** to an Excel file for further use  

## Project Files

- `LGD_Prediction_Linear_Regression.ipynb`: Jupyter Notebook containing the full pipeline (data loading, preprocessing, training, and prediction)  
- `lgd_data.xlsx`: Training dataset  
- `lgd_data_deploy.xlsx`: New data for prediction  

## Author

**Tahir Suleymanov**  
Data Scientist  
[LinkedIn](https://www.linkedin.com/in/tahirsuleymanov/)