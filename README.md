# 📊 Customer Churn Prediction (Telco Dataset)

This is my **first Machine Learning project** 🚀  
I built a **Customer Churn Prediction System** from scratch and deployed it as a **Streamlit app**.  
The goal is to predict whether a telecom customer is likely to churn based on their information.

---

## 🔎 Steps in this Project

### 1. Data Collection
- Dataset: **Telco Customer Churn** (`Telco_Customer_Churn.csv`)  
- Contains customer demographics, services, and billing details.  
- Target variable: **Churn** (Yes / No)

### 2. Data Preprocessing
- Handle missing values  
- Convert categorical features into numeric (encoding)  
- Scale numerical features  
- Split dataset into train/test sets  

### 3. Exploratory Data Analysis (EDA)
- Distribution of churn vs non-churn customers  
- Impact of contract type, tenure, internet service on churn  
- Visualizations (done in `churn_project.ipynb`)

### 4. Model Training
- Tested Logistic Regression and other ML models  
- Selected best model based on accuracy and F1-score  
- Saved trained pipeline as `best_model.joblib`

### 5. Building the App
- Built an interactive **Streamlit app (`app.py`)**  
- Users enter customer details → App predicts **Churn / Not Churn** instantly  

### 6. Results
- Summary of model performance is stored in `results_summary.xlsx`  
- Streamlit app shows prediction results in real-time  

---

## ▶️ How to Run Locally

### 1. Clone this repository
```bash
git clone https://github.com/teenujohn25/Customer-Churn-Prediction-ML.git
cd Customer-Churn-Prediction-ML
