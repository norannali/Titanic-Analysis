# Titanic Exploratory Data Analysis (EDA)

## 📜 Introduction

This project performs an **Exploratory Data Analysis (EDA)** on the Titanic dataset. The aim is to uncover insights regarding the factors that affected the survival of passengers aboard the Titanic. This analysis involves cleaning the dataset, visualizing the distribution of key features, and exploring how different factors (such as age, gender, class, etc.) impacted survival.

## 🛳️ Dataset Overview

The dataset used in this project contains information about the passengers aboard the Titanic, including:

- **PassengerId**: A unique identifier for each passenger.
- **Pclass**: Passenger class (1st, 2nd, 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid by the passenger.
- **Cabin**: Cabin number (many missing values).
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).
- **Survived**: Survival status (0 = No, 1 = Yes).

## 🗂️ Files in this Repository

- **`Titanic_EDA.ipynb`**: Jupyter Notebook with the full EDA, including data cleaning, visualization, and insights.
- **`train.csv`**: The Titanic training dataset used in the analysis.
- **`requirements.txt`**: List of Python dependencies required for running the analysis (if applicable).

## 🧑‍💻 Analysis Techniques

1. **Data Cleaning**:
   - Handling missing values (e.g., filling in missing age values, dropping the "Cabin" column).
   - Encoding categorical features (like "Sex" and "Embarked") for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics to understand the distribution of key features.
   - Visualizations (e.g., histograms, bar plots, pie charts) to identify patterns and correlations.

3. **Survival Analysis**:
   - Exploring how factors like gender, age, and class influenced the likelihood of survival.

## 📊 Key Visualizations

- **Survival Rate Distribution**: Pie chart showing the percentage of survivors vs non-survivors.
- **Age Distribution**: Histogram of passenger ages with survival status.
- **Class Distribution**: Survival rates based on passenger class.
- **Gender and Survival Analysis**: Bar chart comparing survival rates for male and female passengers.

## 🛠️ Libraries and Tools

- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `matplotlib` and `seaborn`: For data visualization.
- `scikit-learn`: Optional, for future machine learning models.

## 🔍 Key Findings

- **Gender**: Female passengers had a higher survival rate than male passengers.
- **Class**: Passengers in higher classes (1st class) had a higher survival rate compared to those in 3rd class.
- **Age**: Younger passengers (especially children) had a higher chance of survival.
- **Embarked**: Passengers who boarded at Cherbourg had a higher survival rate compared to other embarkation points.

## 🚀 Next Steps

- Build a predictive machine learning model to predict passenger survival based on features like age, gender, and class.
- Experiment with feature engineering to improve the model's accuracy.

