# 🫀 Heart Failure Clinical Records - Survival Analysis Dashboard

## 📌 Overview
This project is an **interactive Tableau dashboard** analyzing the Heart Failure Clinical Records dataset.  
It visualizes the relationship between **clinical, demographic, and lifestyle factors** with **patient survival status**.

The dashboard enables healthcare analysts, researchers, and students to identify **key predictors of survival** and uncover patterns in patient outcomes.

---

## 🎯 Objectives
- Compare **survival rates** across different clinical conditions and lifestyle factors
- Explore **distribution patterns** of medical measurements for survivors vs. deceased patients
- Provide an **easy-to-interpret visual tool** for heart failure data analysis

---

## 📊 Dashboard Contents & Metrics

### 1. **Categorical Factors vs. Survival**
- **Diabetes - Survival Status**
  - Percentage of patients with/without diabetes who survived or died.
- **High Blood Pressure - Survival Status**
  - Impact of hypertension on mortality.
- **Sex - Survival Status**
  - Gender distribution and survival rates.
- **Anaemia - Survival Status**
  - Relationship between anaemia and survival.
- **Smoking - Survival Status**
  - Comparison between smokers and non-smokers.

### 2. **Clinical Measurements vs. Survival**
- **Age - Survival Status**
  - Age distribution histograms split by survival outcome.
- **Ejection Fraction - Survival Status**
  - Comparison of heart pumping efficiency between survivors and deceased.
- **Serum Creatinine - Survival Status**
  - Kidney function indicator distribution.
- **Serum Sodium - Survival Status**
  - Blood sodium level differences by outcome.
- **Creatinine Phosphokinase - Survival Status**
  - Enzyme level variations in heart failure patients.
- **Platelets - Survival Status**
  - Platelet count distribution.

### 3. **Time-Based Survival**
- **Age vs. Time - Survival Status**
  - Scatter plot showing follow-up time by age.
- **Time - Survival Status**
  - Histogram of survival time for both groups.

### 4. **Demographic & Clinical Interactions**
- **Age - Sex - Survival Status**
  - Boxplots showing age distribution across gender and outcome groups.

---

## 🗂 Dataset Information
- **Source:** Heart Failure Clinical Records dataset (Kaggle / UCI repository)
- **Records:** 299 patients
- **Key Fields:**
  - Age, Sex, Smoking, Diabetes, Anaemia, High Blood Pressure
  - Ejection Fraction (%)
  - Serum Creatinine (mg/dL)
  - Serum Sodium (mEq/L)
  - Platelets (kiloplatelets/mL)
  - Creatinine Phosphokinase (mcg/L)
  - Time (days of follow-up)
  - Survival Status (Died / Survived)

---

## 🛠 Tools & Technologies
- **Tableau Desktop** – Dashboard design & visualization
- **Tableau Extract (.hyper)** – Optimized dataset storage
- **Heart Failure Dataset** – Source clinical data
