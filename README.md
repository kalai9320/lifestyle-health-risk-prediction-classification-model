# lifestyle-health-risk-prediction-classification-model
Machine learning classification project to assess health risk using BMI, age, sleep, sugar intake, exercise, and lifestyle habits. Complete workflow with data preparation, visualization, Logistic Regression training, feature influence analysis, and interpretation of model performance for real-world health analytics.
# Lifestyle and Health Risk Prediction using Logistic Regression

This project predicts whether an individual is at **High Health Risk** or **Low Health Risk** based on lifestyle and demographic factors. The model is built using **Logistic Regression**.

---

## 📌 Objective
- Predict health risk using common lifestyle factors
- Identify which features contribute most to health outcomes
- Support preventive healthcare decisions using data insights

---

## 📂 Dataset
- **Rows:** 5,000  
- **Columns:** 21  
- No missing or duplicate values

**Features include:**
- Demographics: age, height, weight, marital status, profession  
- Lifestyle: exercise level, sleep duration, sugar intake, smoking, alcohol  
- Derived metric: BMI

**Target Variable**
- `health_risk` → High or Low

Dataset reference:  
https://www.kaggle.com/datasets/miadul/lifestyle-and-health-risk-prediction/data

---

## 📊 Exploratory Data Analysis – Key Findings
- BMI is strongly related to health risk
- Most individuals fall under the high-risk category (slight class imbalance)
- Lifestyle choices have a clear impact on health status

---

## 🧩 Data Preprocessing
- Label Encoding for binary variables (smoking, alcohol, married)
- One-Hot Encoding for multi-category variables (exercise, sugar_intake, profession)
- Standard Scaling applied after train-test split

---

## 🤖 Model Used
- Logistic Regression

**Performance:**
- **Accuracy:** 89.3%
- High recall for high-risk class (important in healthcare)
- Low-risk individuals sometimes predicted as high-risk (safer in real use)

---

## 🔍 Feature Influence Summary
- Lower sugar intake, better sleep, and taller height reduce health risk  
- Smoking, higher age, high BMI, and alcohol consumption increase health risk  
- Lifestyle factors are stronger predictors than profession

---

## 🧪 Tools & Technologies
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-Learn  

---

## 📝 Notebook Includes
- EDA and visualizations  
- Preprocessing and encoding  
- Model training and evaluation  
- Feature importance analysis  
- Interpretation of results  


---

## 👩‍💻 Author
Kalaiselvi G  
Data Science Learner

---

## 🙌 Acknowledgment
Thanks to the dataset contributors and the Python data science community.
