# 🛡️ Fraud Shield - Real-Time Credit Card Fraud Detection App

A machine learning web app to detect fraudulent credit card transactions using XGBoost, Streamlit, and real-world financial data.

---

## 🚀 Tech Stack

- Python, Pandas, Scikit-learn, XGBoost
- Streamlit (interactive web UI)
- SMOTE (to handle class imbalance)
- ROC-AUC Score: **0.978**, F1-Score (fraud): **0.82**

---

## 📊 Dataset

This project uses the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle.

- **Source:** European cardholder transaction data (2013)
- **Size:** 284,807 transactions
- **Fraud Cases:** 492 (very imbalanced)
- **Features:** PCA-transformed anonymized features `V1–V28`, plus `Amount`, and target `Class` (1 = Fraud, 0 = Legit)
- 📝 *Note:* The dataset is not included in this repo due to GitHub’s 100MB file limit. You can download it directly from Kaggle.

---

## 🧪 Features

- Inputs: V1–V28 + Amount
- Real-time fraud prediction with XGBoost model
- Outputs: Fraud/Not Fraud with confidence level
- Clean, responsive Streamlit UI

---

## 💻 Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
