# Titanic Survival Analysis

A comprehensive Exploratory Data Analysis (EDA) project on the Titanic dataset aimed at understanding passenger survival patterns through data cleaning, feature engineering, statistical analysis, and visualization.

---

## Problem Statement

The Titanic disaster remains one of the most studied events in data science due to the availability of passenger information and survival outcomes.

The objective of this project is to analyze passenger demographics, ticket information, socioeconomic status, and travel characteristics to identify factors that influenced survival rates.

Through exploratory data analysis and feature engineering, the project uncovers meaningful patterns that can support future machine learning models for survival prediction.

---

## Overview

This project performs an end-to-end exploratory analysis of the Titanic dataset.

The workflow includes:

* Data cleaning and preprocessing
* Missing value treatment
* Feature engineering
* Statistical analysis
* Correlation analysis
* Data visualization
* Insight generation

The goal is to understand the factors that influenced passenger survival and prepare the dataset for future predictive modeling tasks.

---

## Features

* Missing value handling
* Categorical feature encoding
* Feature engineering
* Survival trend analysis
* Correlation analysis
* Pairwise relationship visualization
* Data-driven insight generation

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Dataset

Dataset: Titanic Passenger Dataset

The dataset contains information about:

* Passenger demographics
* Passenger class
* Ticket fare
* Embarkation port
* Family relationships
* Survival status

---

## Project Structure

```text
Titanic-Survival-Analysis/
│
├── Task_2.ipynb      # EDA notebook
├── titanic.csv       # Dataset
└── README.md         # Documentation
```

---

## Data Cleaning and Feature Engineering

The following preprocessing steps were performed:

* Dropped irrelevant columns:

  * Name
  * Ticket
  * Cabin
  * PassengerId

* Filled missing Age values using median imputation

* Filled missing Embarked values using mode imputation

* Encoded categorical variables:

  * Sex
  * Embarked

* Created a new feature:

```python
FamilySize = SibSp + Parch + 1
```

---

## Visualizations Included

### 1. Survival Count

[Insert Image]

### 2. Survival by Sex

[Insert Image]

### 3. Survival by Passenger Class

[Insert Image]

### 4. Age Distribution vs Survival

[Insert Image]

### 5. Fare vs Survival

[Insert Image]

### 6. Embarkation Port vs Survival

[Insert Image]

### 7. Family Size vs Survival

[Insert Image]

### 8. Correlation Heatmap

[Insert Image]

### 9. Pairwise Relationships (Pairplot)

[Insert Image]

---

## Key Insights

* Female passengers had significantly higher survival rates than male passengers.
* First-class passengers were more likely to survive compared to second- and third-class passengers.
* Younger passengers showed slightly higher survival rates.
* Higher ticket fares were positively associated with survival.
* Embarkation port had a measurable influence on survival outcomes.
* Medium-sized families generally exhibited better survival probabilities.

---

## Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Correlation Analysis
* Statistical Interpretation
* Python Programming

---

## Future Enhancements

* Build machine learning models for survival prediction
* Compare multiple classification algorithms
* Hyperparameter optimization
* Feature importance analysis
* Deploy an interactive dashboard using Streamlit

---
