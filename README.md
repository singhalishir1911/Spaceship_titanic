# Spaceship Titanic
This is the competition on Kaggle to practice Machine Learning Fundamentals and more.

It contains three files: Train.csv, Test.csv and Sample_Submission.csv
## Steps:
### 1. Data Preprocessing:
1. Handled all the missing values in train.csv and test.csv
2. Encoded all string data using OrdinalEncoder and OneHotEncoder
3. Done Feature scaling using StandardScaler to scale down all features
### 2. Choosing of Model
As the output has Binary Classification, I have used Classifiers.

Used Cross Validation to find the best model among:
1. Logistic Regression
2. SVC
3. Decision Tree
4. Random Forest
5. Gradient Bosst
6. XGBoost
7. Ada Boost
8. LightGBM

Received Accuracy:

Logistic Regression accuracy: 79.26%

SVC accuracy: 80.37%

Decision Tree accuracy: 75.02%

Random Forest accuracy: 79.85%

XGBoost accuracy: 80.72%

Gradient Boosting accuracy: 80.87%

Ada Boost accuracy: 78.19%

LightGBM accuracy: 81.20%

Finally, LightGBM model is choosen

### 3. HyperParameter Tuning
Tuned Hyperparameters of LightGBM, using RandomizedSearchCV

LightGBM Accuracy: 81.35%

### 4. Training of model

Trained Model on train.csv after splitting it into X_train and X_test

LightGBM Accuracy: 78.83%

### 5. Creating submission.csv
Created Submsission.csv and submitted on Kaggle
