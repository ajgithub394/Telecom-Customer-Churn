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
