# Titanic Survival Prediction Project

## Objective
The objective of this project is to analyze and predict passenger survival on the Titanic based on historical data. The model will be built using features such as age, gender, class, and family relationships to identify the factors most strongly associated with survival rates.

## 1. Introduction
The Titanic disaster of 1912 is one of the most tragic events in maritime history, where over 1,500 passengers lost their lives. The dataset from this event provides a unique opportunity to analyze the factors that influenced survival, such as age, gender, and class. This project will develop a predictive model and uncover meaningful patterns in the dataset.

## 2. Problem Statement
This project aims to build a model that can predict whether a passenger survived the Titanic disaster based on various features such as passenger's age, gender, class, and family relationships. The goal is to identify the most important factors contributing to survival rates.

## 3. Dataset Details

### Dataset Name:
Titanic Survival Dataset

### Source:
[https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data)

### Files Provided:
- `train.csv`: Contains data with the target variable `Survived` (whether the passenger survived or not).
- `test.csv`: Contains data without the target variable, used for model evaluation.

### Key Columns in `train.csv`:
- `PassengerId`: Unique ID for each passenger.
- `Survived`: Target variable (0 = No, 1 = Yes).
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- `Name`: Passenger’s full name.
- `Sex`: Gender.
- `Age`: Age in years.
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard.
- `Ticket`: Ticket number.
- `Fare`: Fare paid.
- `Cabin`: Cabin number (where available).
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## 4. Tasks

### 1. Data Exploration
- Load the dataset and inspect its structure.
- Explore the distribution of features and look for any trends related to survival.

### 2. Data Cleaning and Preprocessing
- Handle missing values in `Age`, `Cabin`, and `Embarked`.
- Encode categorical features like `Sex` and `Embarked`.
- Create new features such as family size from `SibSp` and `Parch`.

### 3. Exploratory Data Analysis (EDA)
- Visualize survival rates by gender, age, class, and other features.
- Look for patterns that may be predictive of survival.

### 4. Model Building and Evaluation
- Select relevant features and target variable for prediction.
- Split the data into training and testing sets.
- Train a Logistic Regression model and evaluate the accuracy and performance.

## 5. Expected Outcomes
- **Insights into Titanic Survival**: Understand how different factors such as gender, class, and age impacted survival rates.
- **Predictive Model**: A model that can predict whether a passenger survived the disaster based on various features.
- **Performance Evaluation**: Assess the accuracy and performance of the Logistic Regression model.

## 6. Tools and Libraries Used:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
