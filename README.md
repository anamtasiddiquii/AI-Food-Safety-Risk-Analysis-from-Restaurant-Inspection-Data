# AI-Food-Safety-Risk-Analysis-from-Restaurant-Inspection-Data
This project applies data analysis, statistical methods, and machine learning to restaurant inspection data to identify patterns associated with food-safety risks and inspection failures.


An end-to-end data science project analyzing restaurant inspection records to identify food-safety risk patterns, inspection trends, recurring violations, geographic patterns, and factors associated with inspection outcomes.

The project demonstrates practical skills in **data cleaning, exploratory data analysis (EDA), statistical analysis, visualization, temporal analysis, geographic analysis, feature engineering, and predictive modeling** using Python.


## DATASET

[Food Inspections Dataset](https://www.kaggle.com/datasets/chicago/chicago-food-inspections/data)
---

## Project Overview

Food safety inspection datasets often contain messy, inconsistent, and heterogeneous records collected across different locations and inspection periods. This project processes restaurant inspection data and transforms it into meaningful insights that can support **risk identification and proactive food-safety inspection strategies**.

The analysis focuses on:

* Cleaning and preprocessing inspection records
* Exploring restaurant and facility characteristics
* Analyzing inspection outcomes and risk categories
* Identifying temporal inspection patterns
* Studying historical inspection performance
* Analyzing geographic distribution of food-safety risks
* Examining recurring violations
* Developing predictive models for inspection risk

---

## Objectives

* Clean and prepare large-scale restaurant inspection data
* Perform exploratory and statistical analysis of inspection outcomes
* Identify high-risk restaurant and facility patterns
* Analyze inspection results across time and location
* Investigate the relationship between previous and subsequent inspection outcomes
* Identify recurring critical, serious, and minor violations
* Develop predictive features for food-safety risk assessment
* Build machine-learning models to support proactive risk identification

---

## Dataset

The project uses restaurant inspection records containing information such as:

* Inspection ID
* Restaurant / Business Name
* Facility Type
* Risk Category
* Inspection Date
* Inspection Type
* Inspection Result
* Violations
* Address
* ZIP Code
* Latitude
* Longitude

The dataset enables analysis of restaurant-level, temporal, geographic, and violation-related patterns.

---

# Methodology

## 1. Data Cleaning & Preprocessing

The dataset was inspected and prepared for analysis by:

* Handling missing values
* Converting inspection dates into usable datetime features
* Extracting year, month, and day information
* Filtering relevant inspection records
* Removing inactive or invalid business records where appropriate
* Preparing categorical and numerical variables for analysis


## 2. Exploratory Data Analysis

EDA was performed to understand the distribution of:

* Restaurant and facility types
* Risk categories
* Inspection results
* Inspection frequencies
* Business characteristics
* Violations
  


  <img width="883" height="635" alt="image" src="https://github.com/user-attachments/assets/ca0d2800-e759-4872-99d3-1096f6a867d8" />

  <img width="873" height="366" alt="image" src="https://github.com/user-attachments/assets/f12a61cc-0ae9-4a6c-be3c-0b8bfed4f4b4" />
  <img width="883" height="635" alt="image" src="https://github.com/user-attachments/assets/79c3986c-cad3-4d69-8471-da9854a9eefd" />
  






### Facility & Risk Analysis

The distribution of facility types was analyzed across different food-safety risk categories to identify which types of establishments were most frequently associated with higher-risk inspections.

<img width="883" height="635" alt="image" src="https://github.com/user-attachments/assets/66b1328a-40e8-4488-be84-5938085047e0" />
<img width="883" height="635" alt="image" src="https://github.com/user-attachments/assets/22ff6e9a-ccb1-441a-949a-7b3f5ab53486" />


## 3. Inspection Outcome Analysis

Inspection results were analyzed to understand the frequency of:

* Pass
* Pass with Conditions
* Fail
* No Entry
* Not Ready

This analysis helps identify overall inspection-performance patterns and the prevalence of unsuccessful inspections.

<img width="883" height="635" alt="image" src="https://github.com/user-attachments/assets/6de97691-e4a0-4a9c-a5b0-d05cf5ea9c60" />


<img width="883" height="635" alt="image" src="https://github.com/user-attachments/assets/cfceca79-e859-4d88-8b07-cc06cb7ff7e8" />
<img width="883" height="635" alt="image" src="https://github.com/user-attachments/assets/4d284cf9-a324-4274-b476-f1cdf0f0568b" />


## 4. Temporal Analysis

Inspection patterns were examined across different time periods.

The analysis investigates:

* Inspection trends by year
* Inspection trends by month
* Risk distribution over time
* Changes in inspection outcomes
* Frequency of failures across different periods


## 5. Inspection History Analysis

Historical inspection performance was analyzed to determine whether previous inspection outcomes provide useful information about future inspection results.

Restaurant-level inspection histories were constructed using previous inspection outcomes and inspection frequency.

The analysis investigates whether establishments with previous failures are more likely to experience subsequent failures.

**Screenshot:** Insert your previous-vs-current inspection analysis here.

## 6. Geographic Analysis

Restaurant inspection records containing latitude and longitude information were analyzed to examine the geographic distribution of food-safety risk.

The analysis visualizes:

* Restaurant locations
* High-risk facilities
* Medium-risk facilities
* Inspection outcomes
* Geographic concentrations of potential food-safety concerns



## 7. Violation Analysis

Inspection violations were analyzed to identify recurring food-safety issues.

Violation information was transformed into structured indicators to enable analysis of:

* Critical violations
* Serious violations
* Minor violations
* Recurring violation categories
* Violation frequency across establishments

This transformation allows unstructured violation information to be incorporated into statistical and machine-learning analysis.


## 8. Feature Engineering

Features were developed from restaurant inspection histories and violation information.

Example features include:

* Previous inspection result
* Inspection frequency
* Historical failure count
* Critical violation count
* Serious violation count
* Minor violation count
* Facility type
* Risk category
* Geographic information
* Restaurant characteristics

These features provide a structured representation of restaurant inspection behavior for predictive modeling.


## 9. Predictive Modeling

Machine-learning models were explored to identify patterns associated with restaurant inspection risk.

The predictive modeling pipeline includes:

1. Feature preparation
2. Train/test preparation
3. Model training
4. Prediction
5. Model evaluation
6. Comparison of model performance

The modeling stage demonstrates how historical inspection information can be transformed into predictive signals for food-safety risk assessment.





# Technologies & Libraries

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn
* Plotly

### Machine Learning

* Scikit-learn

### Analysis Techniques

* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Temporal Analysis
* Geographic Analysis
* Feature Engineering
* Predictive Modeling

---

# Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization
* Temporal Pattern Analysis
* Geographic Data Analysis
* Restaurant Inspection Analysis
* Violation Analysis
* Feature Engineering
* Predictive Modeling
* Risk Analysis
* Python-based Data Science

---

# Project Relevance

This project demonstrates an applied **data science and public-health risk analysis workflow** using real-world inspection data.

The combination of **messy-data preprocessing, data harmonization, exploratory analysis, statistical reasoning, visualization, temporal and geographic analysis, and predictive modeling** provides a foundation for developing data-driven approaches to food-safety risk assessment and proactive inspection planning.

---

## Project Structure

```text
AI-Driven-Food-Safety-Risk-Analysis/
│
├── food-inspections-in-chicago-eda-and-modeling.ipynb
├── README.md
└── data/
    └── food_inspections.csv
```





