# BIOINFORMATICS
# Heart Failure Clinical Records Analysis
## Biostatistics & Predictive Modeling Project

This repository contains an end-to-end statistical data analysis and predictive modeling framework developed for the course **"Special Topics in Biostatistics"** in the Department of Computer Science and Biomedical Informatics at the **University of Thessaly** (Academic Year: 2023-2024).

---

## 📌 Project Overview & Purpose

The primary objective of this project is to conduct a rigorous **Exploratory Data Analysis (EDA)** and develop a robust **Logistic Regression model** to predict mortality outcomes in patients suffering from heart failure. 

By investigating the complex correlations between diverse clinical biomarkers and patient survival rates, this study aims to highlight critical prognostic risk factors that can enhance clinical decision-making and patient management protocols.

The pipeline is structurally divided into five comprehensive sections covering data preprocessing, statistical profiling, feature importance, modeling, and evaluation.

---

## 📊 Dataset Description

The analysis evaluates the **Heart Failure Clinical Records Dataset**, sourced from the **UCI Machine Learning Repository**. 

### ⏱️ Key Statistics
* **Cohort Size:** 299 patients monitored during their treatment.
* **Data Integrity:** 100% complete dataset (zero missing or null values).
* **Target Feature:** `DEATH_EVENT` (Categorical mortality outcome).

### 🔬 Clinical Variables & Schema

The dataset comprises 13 numeric clinical attributes mapped as follows:

| Variable Name | Description | Data Type | Value Range / Units |
| :--- | :--- | :--- | :--- |
| **age** | Age of the patient | `float64` | Years |
| **anaemia** | Decrease of red blood cells or hemoglobin | `int64` | Binary (0: No, 1: Yes) |
| **creatinine_phosphokinase** | Level of the CPK enzyme in the blood | `int64` | mcg/L |
| **diabetes** | If the patient has diabetes | `int64` | Binary (0: No, 1: Yes) |
| **ejection_fraction** | Percentage of blood leaving the heart at each contraction | `int64` | Percentage (%) |
| **high_blood_pressure** | If the patient has hypertension | `int64` | Binary (0: No, 1: Yes) |
| **platelets** | Platelet count in the blood | `float64` | kiloplatelets/mL |
| **serum_creatinine** | Serum creatinine level in the blood | `float64` | mg/dL |
| **serum_sodium** | Serum sodium level in the blood | `int64` | mEq/L |
| **sex** | Biological gender | `int64` | Binary (0: Female, 1: Male) |
| **smoking** | If the patient is a smoker | `int64` | Binary (0: No, 1: Yes) |
| **time** | Follow-up monitoring period | `int64` | Days |
| **DEATH_EVENT** | **Target Variable:** Mortality outcome | `int64` | Binary (0: Alive, 1: Deceased) |

