# BIOINFORMATICS
Heart Failure Clinical Records Analysis
Project Overview
This report was developed as part of the course Special Topics in Biostatistics in the Department of Computer Science and Biomedical Informatics at the University of Thessaly during the academic year 2023-2024. The project is divided into five sections, which are detailed below.

Data Description
The analysis focuses on the Heart Failure Clinical Records Dataset from the UCI Machine Learning Repository. This dataset includes information from 299 patients who experienced heart failure and were monitored during their treatment. The goal of the study is to investigate the correlation between various clinical characteristics and the mortality outcome, as defined by the DEATH_EVENT variable. Understanding these correlations can contribute to better prediction and management of heart failure patients' conditions.

Dataset Details
The dataset contains 299 heart failure patients and includes the following 13 clinical variables. All variables are numeric, and there are no missing data:

age: Age of the patient (float64)
anaemia: Presence of anaemia (0: No, 1: Yes) (int64)
creatinine_phosphokinase: Level of the CPK enzyme in the blood (int64)
diabetes: Presence of diabetes (0: No, 1: Yes) (int64)
ejection_fraction: Percentage of blood leaving the heart at each contraction (int64)
high_blood_pressure: High blood pressure (0: No, 1: Yes) (int64)
platelets: Platelet count in the blood (float64)
serum_creatinine: Serum creatinine level in the blood (float64)
serum_sodium: Serum sodium level in the blood (int64)
sex: Gender (0: Female, 1: Male) (int64)
smoking: Smoking status (0: No, 1: Yes) (int64)
time: Follow-up period in days (int64)
DEATH_EVENT: Mortality outcome (0: Alive, 1: Dead) (int64)
Purpose
The primary aim of this project is to perform exploratory data analysis (EDA) and develop a logistic regression model to predict mortality in patients with heart failure based on their clinical characteristics.
