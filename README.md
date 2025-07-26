# 🎯 Credit Risk Modelling – ML-Based Loan Default Predictor

<p align="center">
  Predict loan default risk using real-world financial data and machine learning — deployed as a live web app for easy credit scoring.
</p>

---

## 📌 Project Overview

This project aims to predict whether a loan applicant is **high risk** or **low risk** based on their financial and personal information.  
It empowers **banks and lenders** to make smarter credit decisions using **machine learning algorithms**.

> ✅ Built using **50,000+ loan records**, achieving:  
> - 🏆 **AUC = 0.98**  
> - 📈 **KS > 85%**  
> - 🔁 **Recall > 90%** for default class  

---

## 📊 Key Results

- 🔍 Enhanced default prediction with engineered features:
  - **LTI Ratio** (Loan-to-Income)
  - **Average DPN** (Days Past Due)
- ⚖️ Balanced dataset using **SMOTE + Tomek Links**
- ⚙️ Optimized with **Optuna**, reducing hyperparameter tuning time by ~35%
- 🚀 Deployed as a **Streamlit web app** for real-time scoring:
  - Credit Score: **300 – 900**
  - Risk Category: ✅ Low Risk / ❌ High Risk (color-coded)

---

## 📂 Project Structure

```bash
credit_risk_modelling_ml/
│
├── app/
│   ├── main.py                 # Streamlit app interface
│   ├── prediction_helper.py    # Preprocessing & prediction logic
│   └── artifacts/
│       └── model_data.joblib   # Trained model + encoders
│
├── dataset/
│   └── credit_data.csv         # Raw dataset
│
├── notebooks/
│   └── credit_risk_model_jupyter_notebook.ipynb  # EDA + Training
│
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## 🧠 How It Works

1. **User Inputs:** Age, Income, Loan Amount, Employment Type, etc.
2. **Model Processing:** Features are cleaned, scaled, and passed to the ML model.
3. **Predictions:**  
   - A credit score between **300–900**  
   - Risk label: ✅ Low Risk or ❌ High Risk  
   - Color-coded for quick visual understanding

---

## 🛠️ Tools & Technologies

| Category          | Tools                                  |
|------------------|----------------------------------------|
| 🐍 Programming    | Python                                 |
| 📊 Data Handling  | Pandas, NumPy                          |
| 🤖 Machine Learning | Scikit-learn, XGBoost                  |
| 📉 Visualization  | Matplotlib, Seaborn                    |
| ⚙️ Optimization   | Optuna                                 |
| 🔁 Sampling       | SMOTE, Tomek Links                     |
| 🧪 Evaluation     | AUC, KS Statistic, Recall, Precision   |
| 🌐 Deployment     | Streamlit                              |
| 🗃️ Database       | MySQL (Optional)                       |
| 💻 IDE            | PyCharm, VS Code                       |

---

## 🚀 How to Run Locally  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Dheeraj23-08/credit_risk_modelling_ml.git
   cd credit_risk_modelling_ml
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**  
   ```bash
   streamlit run app/main.py
   ```

---

## 📺 Live Demo

🔗 [Check Your Credit Score Instantly](https://creditriskmodellingml-dheerajthalour.streamlit.app/)




