# Titanic Survival Prediction 🚢

This project uses Machine Learning classification algorithms to predict whether a passenger survived the Titanic disaster based on passenger information.

## 📌 Project Objective

The main objective of this project is to build and compare different classification models for predicting Titanic passenger survival.

The target variable is:

- `Survived = 1` → Passenger survived
- `Survived = 0` → Passenger did not survive

## 📊 Dataset

The project uses the Titanic dataset, which contains information about passengers such as:

- Passenger Class (`Pclass`)
- Sex (`Sex`)
- Age (`Age`)
- Number of Siblings/Spouses (`SibSp`)
- Number of Parents/Children (`Parch`)
- Passenger Fare (`Fare`)
- Port of Embarkation (`Embarked`)

## 🤖 Classification Models

The following machine learning classification algorithms are used to predict passenger survival:

### 1. Logistic Regression

Logistic Regression is a classification algorithm used to predict the probability of a passenger surviving the Titanic disaster.

It is useful as a baseline classification model.

### 2. K-Nearest Neighbors (KNN)

KNN predicts the class of a passenger by looking at the classes of the nearest data points.

The value of `k` determines how many neighboring observations are considered.

### 3. Decision Tree Classifier

A Decision Tree makes predictions by creating a series of decision rules based on the features.

For example, the model can learn relationships between features such as sex, passenger class, and age.

### 4. Random Forest Classifier

Random Forest combines multiple decision trees to produce a more reliable prediction.

It generally provides better generalization than a single decision tree.

### 5. Support Vector Machine (SVM)

SVM finds a decision boundary that separates survivors from non-survivors.

It can be effective when the classes have complex boundaries.

## 🔄 Machine Learning Workflow

The project follows these steps:

1. Load the Titanic dataset
2. Explore the dataset
3. Perform data preprocessing
4. Handle missing values
5. Encode categorical variables
6. Select relevant features
7. Split the dataset into training and testing sets
8. Scale features where required
9. Train classification models
10. Make predictions
11. Evaluate model performance
12. Compare the classification models

## 📈 Model Evaluation

The models can be evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score
- ROC Curve
- ROC-AUC Score

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📁 Project Files

```text
Titanic-survival/
│
├── titanic_survivel.ipynb
└── README.md