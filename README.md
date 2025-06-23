## Bank Marketing Project

Project Description

This project analyzes a bank marketing dataset to predict whether a client will subscribe to a term deposit. The dataset is related to direct marketing campaigns (phone calls) of a Portuguese banking institution.

Source

The dataset is sourced from the UCI Machine Learning Repository, available on Kaggle: Bank Marketing Dataset
 
Attributes

The dataset includes various attributes related to bank clients (age, job, marital status, education, default, housing, loan), last contact of the current campaign (contact, month, day_of_week, duration), other attributes (campaign, pdays, previous, poutcome), and social and economic context attributes (emp.var.rate, cons.price.idx, cons.conf.idx, euribor3m, nr.employed). The target variable y indicates whether the client subscribed to a term deposit ('yes' or 'no').

Analysis and Modeling

bank-marketing-project.ipynb Jupyter notebook performs the following steps:

1. Exploratory Data Analysis (EDA): Initial data inspection, descriptive statistics.

2. Data Preprocessing: Handling outliers, feature scaling (StandardScaler), one-hot encoding for categorical variables, and PCA for dimensionality reduction.

3. Imbalanced Data Handling: Uses SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance in the target variable.

4. Model Training: Applies a Support Vector Machine (SVM) model for classification.

5. Evaluation: Reports classification metrics such as classification report, accuracy score, and ROC AUC score.


