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

<img width="917" height="544" alt="Survival Count" src="https://github.com/user-attachments/assets/84b282cf-c282-4148-882a-06e5d0c8f354" />

### 2. Survival by Sex

<img width="914" height="539" alt="Survival by Sex" src="https://github.com/user-attachments/assets/631b96ec-0222-4b97-b09f-552e271b1436" />

### 3. Survival by Passenger Class

<img width="912" height="549" alt="Survival by Passenger Class" src="https://github.com/user-attachments/assets/e5120816-e4a5-4e4f-8a23-aa896147fd84" />

### 4. Age Distribution vs Survival

<img width="916" height="545" alt="Age Distribution vs Survival" src="https://github.com/user-attachments/assets/f27f87be-4a5f-4bef-8d6e-f34a2140280d" />

### 5. Fare vs Survival

<img width="919" height="553" alt="Fare vs Survival" src="https://github.com/user-attachments/assets/f2a229bc-793c-4826-82fb-4d1f2f04a328" />

### 6. Embarkation Port vs Survival

<img width="915" height="546" alt="Embarkation Port vs Survival" src="https://github.com/user-attachments/assets/d27977bd-7a45-4e94-bbaa-4c5462a906b3" />

### 7. Family Size vs Survival

<img width="919" height="538" alt="Family Size vs Survival" src="https://github.com/user-attachments/assets/adbe239c-8a09-43ab-8b79-9951b4552385" />

### 8. Correlation Heatmap

<img width="864" height="535" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/ea166d06-104f-4846-b899-d4f6675153fe" />

### 9. Pairwise Relationships (Pairplot)

<img width="892" height="800" alt="Pairwise Relationships" src="https://github.com/user-attachments/assets/fb1ab65c-1ce9-4dcc-b7eb-e44c72be64bd" />


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
