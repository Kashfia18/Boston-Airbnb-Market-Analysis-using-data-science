# Boston-Airbnb-Market-Analysis-using-data-science
The CRISP-DM method was adopted in this project. The project consists of:
1) Business understanding
  Questions defined:
  a) What drives Boston's nightly price?
  b) What are the busiest time of the year to visit Boston? By how much do prices spike?
  c) Can we get an idea which features are common in high demand listings?
2) Data understanding: Exploratory data analysis was conducted.
3) Data preparation: Data was cleaned and transformed. Some of the transformations included standardization, encoding categorical variables, feature engineering, handling missing values, data type conversion etc.
4) Modeling: Linear regression and XGBoost models were trained.
5) Evaluation: Models were evaluated with metrics (RMSE and r^2) and t-tests.
6) Communication: Here is my blog-post of my findings in Medium:https://medium.com/@kf092010/unlocking-bostons-airbnb-market-b190eb8edea6

Data Source: https://www.kaggle.com/datasets/airbnb/boston

File description:
archive.zip: Data was downloaded in zip format. The zip file consist of the CSV files that were used int his project.
Boston_analysis.ipynb: notebbook containing the analysis

Libraries used in the project:
pandas: 1.4.4
numpy: 1.21.5
sklearn: 1.0.2
xgboost: 2.1.4
shap: 0.48.0
seaborn: 0.11.2
plotly: 5.9.0
matplotlib: 3.5.2

This is the first project completed as part of the Data Scientist nanodegree program of Udacity
Acknowledgements:
Kaggle public domain

License: MIT License
