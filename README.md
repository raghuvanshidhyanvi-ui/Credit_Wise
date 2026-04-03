# 💳 CreditWise - Loan Approval Prediction

## 📌 Overview

**CreditWise** is a Machine Learning project that predicts whether a loan application should be approved or not based on applicant details.
The primary focus of this project is **risk minimization**, i.e., avoiding approval of risky loans.

---

## 🎯 Objective

* Build a reliable loan approval prediction system
* Compare multiple ML models
* **Prioritize precision** to minimize false approvals (high-risk loans)

---

## ⚙️ Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Naive Bayes

---

## 📊 Model Performance & Selection

* **Naive Bayes** achieved the **highest precision**, making it the best choice for this problem

* Since the goal is to **avoid approving risky loans**, precision is more important than recall

* **Logistic Regression** performed well:

  * Balanced **F1-score**
  * Good overall performance
  * However, slightly lower precision than Naive Bayes

* **KNN** performed comparatively lower than the other models

✅ **Final Model Selected: Naive Bayes**

---

## 🧠 Key Insight

In loan approval systems:

* **False Positive = High Risk** (approving a bad loan)
* Therefore, **precision is the most critical metric**

---

## 🔧 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

---

## 📁 Dataset

* `loan_approval_data.csv`

---

## 🔍 Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Model Training (Logistic, KNN, Naive Bayes)
4. Model Evaluation (Precision, Recall, F1-score)
5. Model Selection based on business objective
6. Feature Engineering

---

## 📁 Project Structure

```
CreditWise/
│── loan_approval_prediction.ipynb
│── loan_approval_data.csv
│── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```
git clone https://github.com/raghuvanshidhyanvi-ui/Credit_Wise.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the notebook

```
jupyter notebook
```

---

## 📌 Future Improvements

* Deploy as a web app (Streamlit / Flask)
* Add more advanced models (XGBoost, Random Forest)
* Hyperparameter tuning
* Real-time prediction system

---

## ✨ Author

Dhyanvi Raghuvanshi
