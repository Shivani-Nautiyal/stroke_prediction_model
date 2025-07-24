# 🧠 Stroke Prediction using Machine Learning

This project uses a machine learning model to predict whether a patient is likely to suffer a stroke based on their health parameters. The model is trained on real-world data and aims to assist in early identification of stroke risk.

---

## 📌 Problem Statement

Early prediction of stroke is critical for saving lives and preventing severe health complications. Using patient data such as age, BMI, hypertension, heart disease, etc., this project builds a classification model that can predict the likelihood of a stroke.

---

## 📊 Dataset

The dataset was sourced from Kaggle and includes the following features:

- `gender` – Gender of the patient  
- `age` – Age of the patient  
- `hypertension` – 0: No, 1: Yes  
- `heart_disease` – 0: No, 1: Yes  
- `ever_married` – Marital status  
- `work_type` – Type of employment  
- `Residence_type` – Urban or Rural  
- `avg_glucose_level` – Average glucose level  
- `bmi` – Body Mass Index  
- `smoking_status` – Smoking habit  
- `stroke` – Target variable (1: Stroke, 0: No Stroke)

---

## 🧠 Technologies Used

- **Python**
- **Pandas, NumPy** – Data cleaning and preparation
- **Matplotlib, Seaborn** – Exploratory Data Analysis (EDA)
- **Scikit-learn** – Model training and evaluation

---

## 🛠️ Project Workflow

1. **Data Preprocessing**
   - Checked for null values
   - Performed label encoding for categorical features
   - Handled missing BMI values

2. **Exploratory Data Analysis**
   - Visualized correlations and feature distributions
   - Analyzed stroke occurrences across age, BMI, and glucose levels

3. **Model Building**
   - Applied **Random Forest Classifier** for binary classification
   - Trained and evaluated using train/test split

4. **Evaluation Metrics**
   - Confusion Matrix
   - Accuracy Score
   - Classification Report

---

## ✅ Results

The model achieved good classification performance on the dataset and identified important patterns in the risk factors of stroke.

> *Accuracy: 94.03%*

---

## 🚀 Future Improvements

- Apply ensemble methods like XGBoost
- Deploy using Streamlit or Flask for real-time usage

---

## 👩‍💻 Author

**Shivani Nautiyal**  
📍 Rishikesh, Uttarakhand  
📧 [shivaninautiyal1812@gmail.com] 
🔗 [LinkedIn](https://www.linkedin.com/in/shivani-nautiyal-18xyz) | 

---
