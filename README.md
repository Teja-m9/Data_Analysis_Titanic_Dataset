# Titanic Survival Prediction

## Overview
This project explores the Titanic dataset from Kaggle to analyze factors affecting passenger survival. It includes exploratory data analysis (EDA), data cleaning, and the implementation of a logistic regression model to predict survival outcomes.

## Contents
- Exploratory Data Analysis
- Data Cleaning and Handling Missing Values
- Data Visualization using Seaborn
- Logistic Regression Model Implementation

## Dataset
The Titanic dataset consists of information about the passengers aboard the Titanic, including features such as:
- PassengerId
- Pclass (Ticket class)
- Name
- Sex
- Age
- Sibling/Spouse Aboard
- Parent/Child Aboard
- Fare
- Cabin
- Embarked (Port of Embarkation)
- Survived (Survival status)

## Exploratory Data Analysis (EDA)
The EDA involves:
- Analyzing the distribution of passengers by age, class, and gender.
- Visualizing correlations between features using heatmaps and scatter plots.
- Understanding survival rates through count plots and histograms.

### Key Visualizations
- Histograms for age distribution and fare.
- Heatmaps to identify correlations between features.
- Count plots to compare survival rates across different categories.

## Data Cleaning
In this section, I handled missing values by:
- Filling missing ages with the median age.
- Dropping columns that did not provide significant value for analysis (e.g., Cabin).
- Encoding categorical variables for modeling purposes.

## Logistic Regression Model
A logistic regression model was implemented to classify whether a passenger survived based on their features. The model’s performance was evaluated using accuracy, confusion matrix, and ROC curve analysis.

## Requirements
To run this project, you'll need the following libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

You can install these using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
