# Bank_Customer_Churn_Prediction
##### Introduction : In today’s competitive banking landscape, retaining customers is as critical as acquiring new ones. Predictive analytics is transforming how banks understand and respond to customer behavior. The Bank Customer Churn Prediction Model is a powerful tool that uses data to forecast which customers are likely to leave, allowing banks to take proactive measures to retain them.
##### Project Overview: Bank Customer Churn Prediction
###### This project aims to analyze customer data from a bank and predict the likelihood of a customer leaving (churning). The goal is to build an accurate and interpretable machine learning model to help the bank improve customer retention strategies.
##### Data Loading & Exploration
###### Loaded the Bank Churn Modelling dataset.
###### Explored dataset structure, checked missing values, and summarized key statistics.
###### Dropped irrelevant features (CustomerId, Surname) as they don’t contribute to predictions.
##### Data Preprocessing
###### Applied One-Hot Encoding to categorical variables (Geography, Gender).
###### Balanced the dataset using SMOTE (Synthetic Minority Oversampling Technique) to address class imbalance.
###### Scaled numerical features using StandardScaler for better model performance.
##### Exploratory Data Analysis (EDA)
###### Analyzed churn distribution to understand imbalance.
###### Visualized relationships between features (e.g., correlation matrix, churn vs. demographics).
###### Gained insights into which customer attributes influence churn (e.g., age, tenure, balance, geography).
##### Model Building
###### Split the dataset into training and test sets.
###### Trained multiple machine learning models (Logistic Regression, Decision Tree, Random Forest, etc.).
###### Tuned hyperparameters for improved performance.
##### Model Evaluation
###### Evaluated models using metrics such as Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
###### Compared results across different models to select the best-performing one.
###### Interpreted feature importance to understand which factors drive churn.
##### Outcome
###### Built a predictive churn model with good performance after handling imbalance and scaling.
###### Derived business insights to help banks reduce churn (e.g., focusing on high-risk customer segments).
