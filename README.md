**Credit Score Classification Task**

**Overview**

This project focuses on classifying customers' credit scores into three categories: Poor, Standard, and Good. The dataset used for training and evaluation is train.csv.

**Objectives**

- Perform Exploratory Data Analysis (EDA) to understand dataset features.
- Preprocess the data (handling missing values, encoding categorical features, resampling imbalanced classes, etc.).
- Build a classification model to predict Credit\_Score.
- Evaluate model performance using accuracy and other metrics.
- Generate predictions for new customer data.
-----

**Dataset Information**

- File Name: train.csv
- Number of Samples: Approximately 100,000 rows
- Key Features: 
  - Customer\_ID: Unique identifier for customers.
  - Age, Annual\_Income, Monthly\_Inhand\_Salary: Financial and demographic details.
  - Num\_Bank\_Accounts, Num\_Credit\_Card: Banking-related attributes.
  - Interest\_Rate, Num\_of\_Loan, Outstanding\_Debt: Loan and debt metrics.
  - Payment\_Behaviour, Num\_of\_Delayed\_Payment, Credit\_History\_Age: Payment patterns.
  - Credit\_Utilization\_Ratio, Credit\_Mix: Creditworthiness indicators.
  - Target Column: Credit\_Score (Poor, Standard, Good)
-----
**Dependencies**

Ensure you have the following Python libraries installed:

pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn statsmodels

-----

**Methodology**

1. **Data Loading & Preprocessing**

- Read train.csv using pandas.
- Handle missing values and outliers.
- Encode categorical features using LabelEncoder and OrdinalEncoder.
- Normalize numerical features.
- Balance dataset using RandomOverSampler or RandomUnderSampler.


1. **Exploratory Data Analysis (EDA)**

- Visualize distributions using matplotlib and seaborn.
- Identify correlations and feature importance.

1. **Model Training**

- Split data into training and testing sets.
- Train a RandomForestClassifier.
- Optimize hyperparameters using RandomizedSearchCV.


1. **Evaluation**

- Assess model accuracy, precision, recall, and F1-score.
- Generate classification reports.


1. **Predictions**

- Make predictions on new customer data.
- Interpret model outputs.
-----

**Running the Notebook**

1. Open Jupyter Notebook or Google Colab.
1. Run all cells sequentially.
1. Check outputs for EDA insights and model performance.
1. Use the trained model to predict credit scores on new data.
-----

**Notes**

- The dataset is imbalanced; resampling techniques are applied.
- Feature selection and transformation improve model accuracy.
- The notebook suppresses warnings for a cleaner output.



