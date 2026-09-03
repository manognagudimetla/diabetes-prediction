



## 📌 Overview
This project solves the problem of early detection of diabetes. It takes patient diagnostic data and predicts whether the patient is diabetic, helping with faster and informed healthcare decisions.

**Project Workflow**:  
1. Data exploration  
2. Preprocessing 
3. Model building
4. Evaluation and comparison  
5. Deployment with Streamlit  

---

## 🧠 Models Implemented
- Logistic Regression  
- Random Forest
- XGBoost
- Support Vector Machine(SVM)  

---

## 🌐 Deployment
A **Streamlit web app** was developed to make the model interactive and user-friendly:  
- Accepts patient input (Glucose, BMI, Age, etc.)  
- Returns an instant prediction (**Diabetic / Non-Diabetic**)  

👉 [Live Demo](https://diabetes-prediction-hovcagrettd9ywqvnsgklr.streamlit.app)


---

## ⚙️ Run Locally
Clone the repository and run the app:

```bash
pip install -r requirements.txt
streamlit run app.py
```
---

## 📂 Project Structure

```bash
├── diabetes.csv
├── diabetes_clean.csv
├── notebook.ipynb
├── models
│   ├── logistic_regression.pkl
│   ├── random_forest.pkl
│   ├── scaler.pkl
│   ├── xgboost.pkl
│   └── svm.pkl
├── app.py      
├── requirements.txt
└── README.md
```
---


It provided practical experience in building an end-to-end ML solution, from dataset exploration to deploying a working app.
