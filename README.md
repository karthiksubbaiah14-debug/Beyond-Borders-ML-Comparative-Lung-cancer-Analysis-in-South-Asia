# Beyond-Borders-ML-Comparative-Lung-Cancer-Analysis-in-South-Asia
An end to end data science study of lung cancer across South Asia especially India, integrating regional comparative analysis with Hybrid ML (Decision Tree Classification and K-Means Clustering)
# 🧬 Lung Cancer Data Analysis and Prediction

## 📌 Overview

This project analyzes global lung cancer patient data to identify key risk factors, understand survival patterns, and build predictive models.

A special focus is given to **India and its neighboring countries**, providing comparative insights into regional differences in cancer patterns.

---

## 🎯 Objectives

* Analyze the impact of smoking and air pollution on cancer stages
* Study survival trends based on tumor size and treatment
* Build a machine learning model to predict patient survival
* Segment patients into risk groups using clustering
* Perform **comparative analysis of India vs neighboring countries**

---

## 📊 Dataset

* Total Records: 1500 patients
* Features: 41 variables
* Coverage: Global (WHO regions)

Includes:

* Demographics (Age, Gender)
* Lifestyle (Smoking, Alcohol)
* Environmental factors (Air pollution)
* Clinical data (Tumor size, Symptoms, Treatment, Survival)

---

## 🔍 Analysis Performed

### 1. Exploratory Data Analysis

* Age and gender distribution
* Smoking vs cancer stage
* Air pollution impact
* Tumor size vs survival

---

### 2. Regional Comparative Analysis 🌍

Focused analysis on:

* India
* China
* Pakistan
* Sri Lanka
* Bangladesh
* Nepal
* Bhutan
* Maldives

Key comparisons:

* Cancer stage distribution by country
* Treatment patterns across regions
* Average survival months comparison
* Symptom severity across countries

---

### 3. Feature Engineering

* **Risk Index** created using:

  * Smoking
  * Air Pollution
  * Occupational Hazard
  * Asbestos Exposure
  * Radon Exposure
  * Family History

* **Symptom Score** created using:

  * Coughing
  * Chest Pain
  * Fatigue
  * Wheezing
  * Coughing Blood

---

### 4. Machine Learning

* Model: Decision Tree Classifier
* Accuracy: 63%

Top Features:

* Survival Months
* Tumor Size
* Age

---

### 5. Clustering

* KMeans clustering applied
* Patients grouped into:

  * Low Risk
  * Medium Risk
  * High Risk

---

## 💡 Key Insights

* Smoking significantly increases late-stage cancer risk
* Air pollution strongly correlates with higher cancer severity
* Tumor size is a major factor affecting survival
* Early detection improves survival outcomes

### 🌍 Regional Insights

* India and neighboring countries show a **significant number of non-smoker lung cancer cases**
* Survival rates vary notably across countries
* Treatment approaches differ regionally
* Symptom severity patterns differ across populations

---

## 🛠️ Tools and Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 📁 Project Structure

* `data/` → Dataset
* `notebook/` → Analysis notebook
* `report/` → Detailed report (PDF)
* `requirements.txt` → Dependencies

---

## 🚀 How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run the notebook:
   jupyter notebook

---

## 📌 Conclusion

This project provides a comprehensive analysis of lung cancer risk factors, combining global and regional perspectives. The inclusion of India-focused analysis adds practical relevance for real-world healthcare insights.

---

## 🔮 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Build interactive dashboards
* Extend analysis with real-world hospital data
