# Parkinsons-Disease-EDA_And_Classification
Exploratory Data Analysis of Parkinson’s Disease patient data to uncover key health patterns and risk factors.

## 📌 Project Overview
This project involves exploratory data analysis (EDA) and predictive modeling on a dataset containing information about 2105 patients.  
The primary aim is to uncover health patterns related to Parkinson’s Disease and build models that predict the diagnosis.

---

## 📊 Dataset Details
The dataset includes the following 35 columns:

- **Demographics**: PatientID, Age, Gender, Ethnicity, EducationLevel
- **Lifestyle Factors**: BMI, Smoking, AlcoholConsumption, PhysicalActivity, DietQuality, SleepQuality
- **Medical History**: FamilyHistoryParkinsons, TraumaticBrainInjury, Hypertension, Diabetes, Depression, Stroke
- **Clinical Measures**: SystolicBP, DiastolicBP, Cholesterol levels (Total, LDL, HDL, Triglycerides)
- **Neurological Assessments**: UPDRS, MoCA, FunctionalAssessment
- **Symptoms**: Tremor, Rigidity, Bradykinesia, PosturalInstability, SpeechProblems, SleepDisorders, Constipation
- **Outcome**: Diagnosis (Target Variable)
- **Other**: DoctorInCharge

---

## 🔍 Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing.
- Statistical summaries and visualization of features like Age, Gender, BMI, Smoking Habits, Blood Pressure, Cholesterol Levels, etc.
- Correlation heatmaps to identify important features related to Parkinson’s Diagnosis.
- Distribution analysis between diagnosed and non-diagnosed groups.

---

## 🤖 Machine Learning Models

### 1. Decision Tree Classifier
**Performance:**
- **Accuracy Score**: `87.41%`
- **Classification Report**:
  - Precision: 0.79 (class 0), 0.93 (class 1)
  - Recall: 0.89 (class 0), 0.87 (class 1)
  - F1-Score: 0.83 (class 0), 0.90 (class 1)
  
### 2. Random Forest Classifier
**Performance:**
- **Accuracy Score**: `90.73%`
- **Classification Report**:
  - Precision: 0.84 (class 0), 0.95 (class 1)
  - Recall: 0.92 (class 0), 0.90 (class 1)
  - F1-Score: 0.88 (class 0), 0.93 (class 1)

**Observation:**  
Random Forest outperforms Decision Tree, delivering better accuracy and balanced precision-recall metrics.

---

## 📈 Key Findings
- Higher prevalence of Parkinson’s Disease was observed among older patients with family history and certain lifestyle habits (e.g., poor sleep quality, low physical activity).
- Clinical markers like SystolicBP, DiastolicBP, and Cholesterol levels showed notable variation between diagnosed and non-diagnosed patients.
- The Random Forest model provided a robust classification performance with over 90% accuracy.

---

## ✅ Conclusion
This project successfully combines EDA and machine learning to explore and predict Parkinson’s Disease diagnosis.  
Insights gained from health metrics and lifestyle factors could assist in early intervention strategies.  
Future work could include hyperparameter tuning, model ensembling, and deployment as a simple web application.

---


