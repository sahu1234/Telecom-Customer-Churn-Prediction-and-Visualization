# Telecom-Customer-Churn-Prediction-and-Visualization
This project focuses on predicting customer churn for a telecommunications company using advanced data science techniques and visualizing key insights through an interactive Tableau Public dashboard.

Kaggle Link : https://www.kaggle.com/code/sahilnbajaj/telecom-customer-churn-prediction

Tableau Link : https://public.tableau.com/app/profile/sahil.bajaj5153/viz/TelecomCustomerChurnAnalysisDashboard_17251839663140/Dashboard1

The project is divided into several stages:

Data Preprocessing:

The Telecom Churn dataset is cleaned and prepared by handling missing values, encoding categorical variables, and conducting feature engineering. Important features such as tenure bins and interaction terms are created to enhance the model's predictive power.

Balancing Classes:
To address the class imbalance between churned and non-churned customers, the Synthetic Minority Over-sampling Technique (SMOTE) is applied. This helps in improving the model's ability to accurately predict churn by creating a balanced dataset.

Model Building:
A Random Forest classifier is trained on the balanced dataset. Hyperparameter tuning is conducted using GridSearchCV to identify the optimal parameters, leading to a robust model with a high ROC-AUC score of 0.919. The model achieves an accuracy of 83.8%, with balanced precision and recall for both churn and non-churn classes.

Feature Importance Analysis:
The feature importance analysis reveals that MonthlyCharges, TotalCharges, Contract, and Tenure are the most influential factors in predicting customer churn. These insights are critical for the business to focus on key areas for improving customer retention.

Interactive Dashboard Creation:
An interactive Tableau Public dashboard is created to visualize the key findings. The dashboard includes visualizations such as churn rate by contract type, monthly charges vs. churn, tenure vs. churn, and a feature importance bar chart. The dashboard allows users to interact with the data, explore different customer segments, and gain actionable insights for reducing churn.

Project Outcome:
The project delivers a highly effective predictive model and an interactive dashboard that enables stakeholders to identify at-risk customers, understand the key drivers of churn, and implement targeted retention strategies. The dashboard and model are tools that can be integrated into the company’s decision-making processes to enhance customer loyalty and reduce churn rates.
This project showcases the integration of data science and data visualization to solve a real-world business problem, making it an excellent example of applying advanced analytics in the telecom industry.
