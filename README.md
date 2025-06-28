# Telecom-Customer-Churn

In this project, I analysed the data of a telecom company and it's customers and predicted whether they will churn(leave the company) or not.

- First, I did some data cleaning, treating null values and changing the datatypes of some features
- Then, I did some Exploratory Data Analysis and found out the relation between each feature and Churn
- I plotted heatmaps, boxplots and violin plots to visually show the dependance
- I used XGBoost to predict churn. First, I tried Random Forest Classification but it did not give good results.
- I realised that accuracy doesn't matter in this case, recall and precision are the metrics that we should pay attention to.
- We only want to predict the churners correctly so that we can target those customers with ads and schemes.
- Then, I plotted Precision-Recall curve to show the tradeoff between these quantities and ROC curve for showing results at different threshold values.
- Finally, I used SHAP to plot some characteristics related to the model's prediction.  


![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-Model-green?logo=xgboost)
![Matplotlib](https://img.shields.io/badge/Matplotlib-EDA-red?logo=matplotlib)
![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blue?logo=seaborn)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-purple)
