# m5-forecasting-challenge
## Introduction
This project is for the kaggle m5 forecasting challenge to brush up my time series forecasting skills. It is to estimate, as precisely as possible, the point forecasts of the unit sales of various products sold in the USA by Walmart.

The dataset comprises 60980 products from 10 stores across three states. As the dataset is too large for my laptop to process it efficiently. All the works are done using Kaggle notebook. Thus, the output will not be shown in the notebooks pushed here, instead, I will use figures to demonstrate where clarification is needed.

The RMSSE score is significantly better than all the baseline models.

## Directory
 - data_munging.ipynb
   - preparing and merging datasets
 - effect-of-holiday-by-dept.ipynb
   - EDA and visualisation to determine to effect of holidays on the demand of product of different department, can be modified to visualise other relationship
 - forecasting.ipynb
   - forecasting and producing submission
<br><br><a href="https://www.kaggle.com/c/18599/download-all">link to datasets</a>

## Requirements
pystan
```sh
pip install pystan
```
fbprophet
```sh
pip install fbprophet
```
