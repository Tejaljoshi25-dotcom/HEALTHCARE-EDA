# HEALTHCARE-EDA : Spotting Stroke Risk Factors Early


# Stroke Risk Factor Analysis using Exploratory Data Analysis (EDA)

##  Project Overview

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on a healthcare dataset to identify demographic and clinical characteristics associated with stroke occurrence. The analysis focuses on understanding data quality, feature distributions, statistical relationships, and patterns that may help healthcare professionals identify high-risk patient groups.

---

##  Objective

The primary objective of this project is to:

* Explore demographic and clinical features related to stroke.
* Identify significant patterns and feature distributions.
* Detect missing values and outliers.
* Examine relationships between patient characteristics and stroke occurrence.
* Generate actionable insights that could support future predictive modeling and healthcare decision-making.

---

##  Research Questions

This analysis investigates the following questions:

1. Are older individuals more likely to experience a stroke?
2. Is stroke occurrence more common among patients with hypertension or heart disease?
3. How are blood glucose levels and BMI distributed among stroke and non-stroke patients?
4. Does smoking history show noticeable differences between stroke and non-stroke populations?
5. Which patient characteristics appear most strongly associated with stroke?

---

##  Dataset Description

The dataset contains demographic, lifestyle, and clinical information for individual patients.

| Feature           | Description                                 |
| ----------------- | ------------------------------------------- |
| id                | Unique patient identifier                   |
| age               | Patient age                                 |
| hypertension      | Hypertension status (0 = No, 1 = Yes)       |
| heart_disease     | Heart disease status (0 = No, 1 = Yes)      |
| ever_married      | Marital status                              |
| work_type         | Employment category                         |
| Residence_type    | Urban or Rural residence                    |
| avg_glucose_level | Average blood glucose level                 |
| bmi               | Body Mass Index                             |
| smoking_status    | Smoking history                             |
| stroke            | Target variable (0 = No Stroke, 1 = Stroke) |

---

## 🛠 Data Preprocessing

* Checked dataset dimensions and data types.
* Identified missing values.
* Imputed missing BMI values using the **median**, as BMI exhibited a right-skewed distribution with several outliers.
* Examined duplicate records.
* Performed descriptive statistical analysis.

---

##  Exploratory Data Analysis

The analysis included:

* Univariate analysis
* Bivariate analysis
* Distribution analysis
* Boxplots for outlier detection
* Correlation analysis
* Categorical feature comparison
* Numerical feature comparison
* Age group analysis
* Clinical risk factor analysis

---

##  Key Findings

### 1. Age is the Strongest Associated Feature

Older patients show substantially higher stroke occurrence compared to younger age groups. Stroke cases increase noticeably among senior populations.

### 2. Blood Glucose Levels

Patients with stroke generally exhibit higher average glucose levels than non-stroke patients, suggesting a positive association between elevated glucose levels and stroke occurrence.

### 3. BMI Distribution

BMI values among stroke patients are primarily concentrated within the overweight range, although considerable overlap exists between stroke and non-stroke groups.

### 4. Hypertension and Heart Disease

Stroke occurrence is considerably higher among patients diagnosed with hypertension or heart disease compared with those without these conditions.

### 5. Smoking Status

Patients who currently smoke or formerly smoked display relatively higher stroke proportions than those who never smoked, although the relationship is less pronounced than age or cardiovascular conditions.

### 6. Correlation Analysis

Age demonstrates the strongest positive association with stroke among the available numerical variables, while hypertension and heart disease also exhibit meaningful positive relationships.

---

##  Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

##  Conclusion

The exploratory analysis indicates that stroke occurrence is associated with multiple demographic and clinical characteristics rather than a single factor. Age appears to be the most influential variable, while hypertension, heart disease, elevated blood glucose levels, and smoking history also show meaningful associations.

These findings provide valuable insights for feature selection and serve as a strong foundation for future predictive modeling and machine learning applications in healthcare.

---

##  Future Work

* Build classification models to predict stroke occurrence.
* Address class imbalance using techniques such as SMOTE.
* Perform feature engineering.
* Compare multiple machine learning algorithms.
* Evaluate model performance using ROC-AUC, Precision, Recall, and F1-score.


*AUTHOR*
TEJAL JOSHI 
(DATA SCIENTIST/ RESEARCHER)
