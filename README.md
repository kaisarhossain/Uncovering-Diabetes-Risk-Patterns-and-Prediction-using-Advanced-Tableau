# 🩺 Uncovering-Diabetes-Risk-Patterns-and-Prediction-using-Advanced-Tableau
Leveraging Tableau for visual data storytelling, turning raw health records into intuitive, interactive visualizations using Tableau that highlight how demographic, lifestyle, heredity and clinical factors contribute to diabetes risk. Further, the integration of predictive modeling using TabPy enables real-time classification of diabetes risk.

---

An end-to-end **AI-driven clinical analytics solution** for exploring health indicators and predicting diabetes risk based on lifestyle, demographic, and biometric factors.

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://python.org)
[![Tableau](https://img.shields.io/badge/Tableau-Analytics%20Dashboards-orange.svg)](https://tableau.com)
[![TabPy](https://img.shields.io/badge/TabPy-Model%20Deployment-green.svg)](https://github.com/tableau/TabPy)
[![License](https://img.shields.io/badge/License-Apache-yellow.svg)](https://www.apache.org/licenses/LICENSE-2.0.txt)

---

## 🚀 Overview

Diabetes is a disease that arises from a complex interplay between genetic predisposition, physiological dysfunction, medical condition and lifestyle behaviors. Despite the abundance of medical data, translating these data into actionable insights for early detection and prevention remains a major challenge, particularly for non-clinical stakeholders such as policy planners and community health workers.

This project bridges that gap by leveraging Tableau for visual data storytelling, turning raw health records into intuitive, interactive visualizations using Tableau that highlight how demographic, lifestyle, heredity and clinical factors contribute to diabetes risk. Further, the integration of Python predictive modeling (using TabPy) enables real-time classification of diabetes risk, offering a complete analytical pipeline from exploration to prediction.


**Project Objectives**:
The project’s primary goal is to explore, visualize, and interpret the relationships between these health indicators and diabetes risk levels using Tableau’s advanced analytics and visualization capabilities. The analysis supports both preventive healthcare insights and data-driven decision-making for health professionals, researchers, and policy designers.

The project supports both preventive healthcare analytics and clinical decision support, focusing on five core objectives:

1.	Identify Critical Risk Factors:
Determine which physiological, behavioral, and hereditary features (e.g., BMI, glucose levels, inactivity, family history) are most predictive of diabetes.
2.	Explore Lifestyle and Demographic Trends:
Understand how variables such as age, gender, education, and physical activity influence diabetes prevalence.
3.	Segment Population by Risk Levels:
Use Tableau’s clustering and parameter controls to classify individuals into Low, Moderate, and High-Risk groups.
4.	Differentiate Preventable vs. Non-Preventable Risks:
Highlight lifestyle-modifiable risk factors (exercise, diet, smoking) versus inherent or hereditary ones.
5.	Predictive Modeling:
Integrate a Python-based predictive model (via TabPy) that classifies individuals as Diabetic (Yes/No) and provides a confidence score.


The system analyzes:
- **Demographics**
- **Lifestyle behaviors**
- **Health history**
- **Biometric indicators**
- **Glucose/HbA1c measurements**

A deployed ML model (via **TabPy**) allows **real-time diabetes risk prediction** directly inside Tableau dashboards.

---

## Dataset and Calculated Fields Overview 📊
The dataset contains 31 columns and 100,000 individual patient records, where each record represents a unique health profile. Every profile includes a binary diabetes diagnosis (Yes/No) and a risk score, indicating the likelihood of being diabetic. This comprehensive structure enables both individual-level and population-level analysis, supporting detailed exploration of health patterns, risk correlations, and predictive factors across diverse patient demographics.

The dataset integrates a mix of continuous and categorical variables to capture both measurable clinical metrics and behavioral characteristics:

**Continuous Variables:** Age, Heart Rate, Glucose (Fasting & Postprandial), Insulin Level, Diet Score, etc. — offering quantitative insight into physiological and lifestyle influences on diabetes risk.
**Categorical Variables:** Gender, Smoking Status, Physical Activity Level, Family History of Diabetes, etc. — representing qualitative determinants of health behavior and predisposition.
**Derived and Calculated Fields:** To enhance the interpretability of raw data and support advanced visual analytics, several calculated and derived fields were introduced:

**Categorical Groupings:**
Age Category, Activity Category, BMI Category, Sleep Category, Screen Time Category — for simplified trend segmentation.
**Binary Health Indicators:**
Cardiovascular (Yes/No), Family History (Yes/No), Hypertension History (Yes/No), Diabetes Diagnosed (Yes/No) — for easy classification of key risk factors.
**Advanced Analytical Fields:**
Family Cardiac Combo, Hypertension History Category, Risk Cluster, and Risk Cluster (Weighted) — used for clustering and composite health risk assessment.

**Analytical Strength:**
With 100,000 diverse records and 31 multidimensional features, the dataset supports:
- Robust segmentation across age, gender, income, education levels etc.
- Behavioral pattern analysis involving diet, activity, sleep habits etc.
- Insight into hereditary and comorbid health influences.
- Correlation mapping among clinical biomarkers like glucose, insulin, HbA1c etc.

This structure provides a holistic foundation for data-driven exploration, pattern discovery, and predictive modeling within the domain of diabetes risk analytics.

**Data Source:** https://www.kaggle.com/datasets/mohankrishnathalla/diabetes-health-indicators-dataset

## Model Evaluation 🧠📉
Model Development: Two machine learning models explored (Python Notebook attached):
•	K-Nearest Neighbors (KNN)
•	Random Forest Classifier
 
Best Model: Random Forest 
•	Accuracy: 92%
•	AUC Score: 94%
•	F1 Score: 93% (Positive prediction), 92% (Negative prediction 

## 🔍 Key Features

### 🧬 **1. Advanced Exploratory Analytics**
- Age-based diabetes prevalence  
- BMI and diet score influence  
- Sleep vs. screen time behavior  
- Cardiovascular & hypertension profiles  
- Clinical biomarker relationships (HbA1c, fasting glucose, insulin)

### 📊 **2. Tableau Dashboards**
- Risk Distribution Dashboard  
- Clinical Deep-Dive Dashboard  
- Lifestyle Impact Dashboard  
- Manual & automatic segmentation (Clustering)

### 🤖 **3. Real-Time ML Model Integration (TabPy)**
Predicts:
- **Diabetes Yes/No**
- **Risk Level (Low / Moderate / High)**
- **Confidence score**

**Features used:**
- HbA1c  
- Glucose (fasting + postprandial)  
- BMI  
- Age  
- Physical activity  
- Family history  
- Systolic blood pressure  

### 🔮 **4. Automated Clinical Insights**
- Trend line analysis  
- Risk correlation summaries  
- Cluster profiling  
- Biomarker relationships  

---

## Getting Started 🏁
### TabPy Model Deployment
tabpy

### Deploy your ML model
python TabPy/deploy_model.py

## 🧾 Analytics Covered
📌 1. Demographics
Age
Gender
Ethnicity

📌 2. Lifestyle Behaviors
Diet score
Screen time
Sleep hours
Smoking / Alcohol
Physical activity

📌 3. Medical History
Family history
Hypertension
Cardiovascular disorders

📌 4. Clinical Biomarkers
HbA1c
Glucose (Fasting & Postprandial)
Insulin
Cholesterol panel
Systolic / Diastolic BP

## 📈 Example Insights Generated
Higher BMI groups show increased diabetes prevalence
HbA1c sharply rises with obesity categories
Sedentary individuals (high screen time, low sleep) show higher risk
Insulin and fasting glucose demonstrate strong positive correlation
Combining Age + BMI + HbA1c forms strong predictor of risk clusters

## 💡 Future Enhancements
AR-based health visualization
Automated data ingestion pipeline
Deep learning risk model (LSTM for time series)
EHR integration
Patient-level progress tracking

## 👨‍💻 Author
Mohammed Golam Kaisar Hossain Bhuyan
AI | ML | Deep Learning | Data Analytics
🔗 LinkedIn: https://www.linkedin.com/in/kaisarhossain
🔗 GitHub: https://github.com/kaisarhossain


## 🪪 License
Licensed under Apache 2.0 License.
You are free to use, modify, and distribute.
