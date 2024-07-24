# Titanic_EDA

## Introduction
This repository contains a comprehensive exploratory data analysis (EDA) of the Titanic dataset. The objective is to analyze the data to uncover patterns and insights, which can be useful for predictive modelling and understanding the factors that influenced passenger survival.

## Dataset Information
The Titanic dataset provides information on the passengers who were aboard the Titanic, including their demographics, class, fare, and survival status. This dataset is a classic example used in data science and machine learning for classification problems. 
Columns:
- PassengerId: Unique ID for each passenger
- Survived: Survival (0 = No, 1 = Yes)
- Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name: Name of the passenger
- Sex: Gender of the passenger
- Age: Age of the passenger
- SibSp: Number of siblings/spouses aboard the Titanic
- Parch: Number of parents/children aboard the Titanic
- Ticket: Ticket number
- Fare: Passenger fare
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Results
The EDA script will generate several visualizations and statistical summaries to help understand the data. Key findings will include survival rates by gender and passenger class, age and fare distributions, and correlations between features.

## Visualizations
- Survival Rate by Gender: Comparison of survival rates between male and female passengers.
- Survival Rate by Passenger Class: Analysis of how survival rates differ across passenger classes.
- Age Distribution: Histogram and KDE plot of passenger ages.
- Fare Distribution: Histogram and KDE plot of passenger fares.
- Pairplot: Relationships between key features.
- Correlation Matrix: Heatmap showing correlations between features.

## Limitations
- The dataset has missing values, particularly in the Age, Cabin, and Embarked columns, which required imputation or removal.
- The analysis is descriptive and does not include predictive modelling.

## Future Work
- Build predictive models to estimate passenger survival based on the available features.
- Explore feature engineering techniques to improve model performance.
- Perform deeper analysis on textual data in the Name and Ticket columns.
