# 💳 Credit Risk Predictor

> A Machine Learning project that predicts whether a loan applicant is **high risk or low risk** based on financial and demographic attributes.

This project demonstrates how **machine learning can assist financial institutions in evaluating loan applicants and minimizing default risk.**

---

## 📌 Project Overview

Banks and financial institutions face significant losses due to **loan defaults**.
This project uses **Machine Learning algorithms** to analyze applicant information and predict the **creditworthiness of a borrower**.

The model evaluates several factors like:

* Income
* Age
* Loan Amount
* Credit History
* Employment Status
* Debt-to-Income Ratio

Based on these features, the system predicts:

* ✅ **Low Risk Applicant**
* ⚠️ **High Risk Applicant**

---

## 🚀 Key Features

✔ Data Cleaning & Preprocessing
✔ Exploratory Data Analysis (EDA)
✔ Feature Engineering
✔ Machine Learning Model Training
✔ Model Evaluation Metrics
✔ Prediction System for New Applicants

---

## 🧠 Machine Learning Workflow

```
Data Collection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Credit Risk Prediction
```

---

## 🛠 Tech Stack

| Technology           | Purpose               |
| -------------------- | --------------------- |
| Python               | Programming Language  |
| Pandas               | Data Manipulation     |
| NumPy                | Numerical Computation |
| Scikit-Learn         | Machine Learning      |
| Matplotlib / Seaborn | Data Visualization    |
| Joblib               | Model Saving          |

---

## 📂 Project Structure

```
credit-risk-predictor
│
├── data
│   └── credit_data.csv
│
├── model
│   └── credit_model.pkl
│
├── train_model.py
├── predict.py
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Description

The dataset contains information about loan applicants including:

| Feature           | Description                            |
| ----------------- | -------------------------------------- |
| Age               | Applicant age                          |
| Income            | Monthly or yearly income               |
| LoanAmount        | Requested loan amount                  |
| CreditHistory     | Previous loan repayment history        |
| EmploymentStatus  | Employed / Self-employed / Unemployed  |
| DebtToIncomeRatio | Debt compared to income                |
| Risk              | Target variable (High Risk / Low Risk) |

---

## ⚙ Installation

Clone the repository:

```bash
git clone https://github.com/NarendraXD/credit-risk-predictor.git
cd credit-risk-predictor
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶ Running the Project

### Train the Model

```bash
python train_model.py
```

### Make Predictions

```bash
python predict.py
```

---

## 📈 Model Evaluation

The model is evaluated using standard classification metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

These metrics help determine how well the model distinguishes between **high-risk and low-risk borrowers**.

---

## 🔮 Future Improvements

* Deploy model using **FastAPI**
* Create a **web interface for predictions**
* Add **feature importance visualization**
* Improve model using **XGBoost or Random Forest**
* Deploy the project on **cloud platforms**

---

## 💼 Why This Project Matters

Credit risk prediction is widely used in:

* Banking
* FinTech
* Loan approval systems
* Financial analytics

This project demonstrates practical knowledge of:

* **Machine Learning Pipeline**
* **Data Preprocessing**
* **Model Training & Evaluation**
* **Predictive Analytics**

---

## 👨‍💻 Author

**Narendra Ahirwar**

AI & Data Science Student
Interested in **Machine Learning, Data Analytics, and Artificial Intelligence**

🔗 GitHub
https://github.com/NarendraXD

🔗 LinkedIn
(Add your LinkedIn profile link)

---

## ⭐ Support

If you find this project useful, consider giving the repository a **star ⭐**.
