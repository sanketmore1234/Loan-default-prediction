# Loan-default-prediction
Predict defaulters from loan dataset

# Libraries Used
1. Pandas
2. Scikit Learn
3. Numpy

# Algorithms Used
1. Logistic Regression
2. Ridge Classifier
3. Decision Tree Classifier

# Data cleaning
Drop unnecessary columns which add little value to the model

# Data Transformation
One hot encode categorical columns (list status, application type) - by identifying object type columns

# Hyper Parameter Tuning
Used gridsearch CV for hyper parameter tuning , 
pipeline of - standard scalar, polynomial features, 

# Cross Validation
k fold cross validation, used scoring parameter as f1 (since the false positives were more important)

Used weights as balanced since one class was very less than others

# Performance Criteria
Selected the best performing model considering F1 score

F1 - combined metric of precision and recall scores. Often used as a criteria in case of imbalanced sets/ where both class prediction/ one class prediction is important
