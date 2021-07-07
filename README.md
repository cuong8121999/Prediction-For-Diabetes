# Prediction-For-Diabetes
It consists of code and data for building model

## Data
Data is taken from https://www.kaggle.com/uciml/pima-indians-diabetes-database that including:
1. Features are relative to the diabetes such as (Glucose, BloodPressure, Insulin, etc)
2. The binary labels for each row with 0s represent for not having disease and 1s represent for having disease.


## Processes for Building Model:
1. Importing packages for handling, visualizing data and packages for Classification models (KNN, DecisionTree, Random Forest, etc)
2. Loading the data and doing some basic EDA (Exploratory Data Analysis)
3. Preprocessing data to make it clean before giving to models
4. Splitting data into training and testing set
5. Doing Stratified K-Fold (Cross Validition) on training set to generalize accuracy of models before testing
6. Choosing the model having the highest accuracy score.
7. Tuning hyperparameters of the choiced model to maximize the accuracy score of model
8. Using Confusion Matrix, Precision Score, Recall Score, F1 Score and ROC - AUC to check how well the model did
