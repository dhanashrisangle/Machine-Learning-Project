# Machine-Learning-Project

# Loan Default Prediction Project Overview
This project involves predicting loan default using machine learning techniques. 

# Project Steps:
 ## Data Import and Exploration:
 
* Libraries such as numpy, pandas, seaborn, and matplotlib are imported.
* The dataset Loan_default.csv is loaded into a Pandas DataFrame (df).
* Data exploration is done using methods like head(), info(), and describe() to understand the dataset's structure and contents.


## Data Preprocessing:

* Irrelevant columns like 'LoanID' are dropped.
* Categorical variables are one-hot encoded using pd.get_dummies().
*Numerical features are scaled using StandardScaler to standardize their range.


## Data Visualization:

Visualization techniques like count plots, bar plots, and heatmaps are used to explore data distributions and relationships between features.

## Handling Class Imbalance:

Class imbalance in the target variable ('Default') is addressed using Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset.

## Model Training and Evaluation:

* Various classification models (Logistic Regression, Random Forest, Decision Tree) are trained on the preprocessed data.
* Model performance is evaluated using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
  
# Results and Conclusion:

* Model performance metrics and visualizations (like ROC curves) are used to compare and select the best-performing model (XGBoost).
* Insights from feature importance analysis (Mutual Information) highlight key predictors of loan default (DTIRatio, InterestRate, LoanTerm).
*This project provides a detailed framework for loan default prediction, showcasing the use of data preprocessing, visualization, model training,
 and evaluation techniques for effective machine learning analysis. The findings aim to guide decision-making processes in the financial domain.






