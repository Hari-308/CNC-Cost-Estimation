# CNC Machining Cost Prediction

This project predicts the estimated cost of CNC machining based on product dimensions, material type, and other features.
I created a dataset with web scraping and manual collection and cleaned dataset with 200 entries covering real-world machining scenarios.
The workflow includes data preprocessing, feature engineering, and visualization.
XGBoost Regressor was chosen for its high accuracy in tabular data prediction.
The final model achieved an R² score of 0.86 and is stored as a JSON file.
Exploratory Data Analysis (EDA) was conducted using seaborn and matplotlib.
Categorical features were label-encoded for model compatibility.
The dataset includes both categorical and numerical data.
This project can help industries estimate machining costs efficiently.
Future work includes model deployment via a web application interface.
