# universal-bank-loan-prediction-Python
Classification Project – Predicting customer loan acceptance using the Bank loan dataset


Used  one dataset suitable for exploratory data analysis and machine learning modeling

Steps:
1.	Import the dataset: Load the data into your analysis environment.
2.	Display records: Show the first 5 and last 5 records of the dataset.
3.	Identify data types: Check and note the data types for each variable.
4.	Missing entries: Determine the number of missing entries per variable.
5.	Duplicate records: Identify and count any duplicate records.
6.	Univariate analysis: Conduct this analysis on all variables, creating appropriate visualizations.
7.	Outlier detection: Use the Local Outlier Factor (LoF) method to identify outliers.

8.	Bivariate analysis: Perform at least one analysis for each of the following hypothesis tests:
-	Chi-square test to assess independence between two categorical variables.
-	Correlation analysis to examine relationships between two numeric variables.

  
9.	Check for presence of collinearity and multi-collinearity and address it appropriately.
10.	Encode the data if required (if there are categorical independent variables).
11.	Split the dataset into training and testing subsets.
12.	Scale the training data and use the same scaler to also scale the test data. (use scaled data for algorithms requiring scaling)


13.	Perform PCA. Based on outcome, recommend if Principal Components would be useful for data preparation or not. 

14.	Depending on prediction goal, refer to appropriate section below: 
-	Classification: Build models based on atleast 3 different algorithms
  i.	Logistic Regression / DecisionTreeClassifier / LDA: Choose any one of these 3. 
  ii.	KNN, SVM, RandomForest, AdaBoost, XGBoost: For models other than KNN, tune upto 3 hyperparameters using GridSearchCV.


15.	Check for overfitting and take steps to address it

Note: Dataset obtained from Kaggle.
