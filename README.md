<!-- PROJECT SHIELD BADGES -->
![Stars](https://img.shields.io/github/stars/YourUsername/customer-churn-prediction?style=social)
![Forks](https://img.shields.io/github/forks/YourUsername/customer-churn-prediction?style=social)
![Issues](https://img.shields.io/github/issues/YourUsername/customer-churn-prediction)
![Last Commit](https://img.shields.io/github/last-commit/YourUsername/customer-churn-prediction)
![License](https://img.shields.io/github/license/YourUsername/customer-churn-prediction)

<!-- PROJECT TITLE -->
<h1 align="center">📉 Customer Churn Prediction | Telco Dataset</h1>

<p align="center">
  <b>Predicting customer churn using machine learning.</b><br>
  <i>Logistic Regression | Data Preprocessing | EDA | Model Evaluation | Visualizations</i>
</p>

---

## 🔥 Key Features

- 📊 Exploratory Data Analysis (EDA) with interactive plots  
- 🧹 Advanced data cleaning and preprocessing (handling missing values, encoding, scaling)  
- 🤖 Logistic Regression for churn classification  
- 🎯 Model evaluation (Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix)  
- 📈 Feature correlation & importance analysis  
- 📂 Jupyter notebook with step-by-step explanations  

---

## ✨ Screenshots

<p align="center">
  <img alt="Churn Count Plot" src="screenshots/churn-count.png" width="350">
  <img alt="Classification Report" src="screenshots/classification-report.png" width="350">
</p>

---
## 🚀 Quick Start

```bash
# 1️⃣ Clone the repository
git clone https://github.com/YourUsername/customer-churn-prediction.git
cd customer-churn-prediction

# 2️⃣ Install dependencies
pip install -r requirements.txt

# 3️⃣ Launch Jupyter Notebook
jupyter notebook main.ipynb
```


🧰 Project Structure
customer-churn-prediction/
├── main.ipynb                 # Jupyter notebook with code & analysis
├── WA_Fn-UseC_-Telco-Customer-Churn.csv   # Dataset
├── requirements.txt            # Dependencies
├── screenshots/                # Output screenshots
└── README.md                   # Project README

📇 Dataset

Source: Kaggle: Telco Customer Churn

Rows: 7,043

Features: Demographics, account info, service usage, and Churn (target variable)

⚡ Workflow

Load dataset & libraries

Explore and visualize churn patterns (gender, contract type, payment methods, etc.)

Handle missing values (e.g., TotalCharges) and outliers

Encode categorical variables, scale numeric features

Train & test split for model building

Logistic Regression model training

Evaluate performance with multiple metrics

Visualize confusion matrix & ROC curve

📊 Results
| Metric    | Value |
| --------- | ----- |
| Accuracy  | 0.81  |
| Precision | 0.72  |
| Recall    | 0.65  |
| F1-Score  | 0.68  |

✔️ Insights:

~26.6% of customers churned

Customers with Month-to-Month contracts & Electronic Check payments churned the most

Customers without partners/dependents or without online security/tech support showed higher churn

High monthly charges correlated with higher churn probability

🛠️ Requirements

Python 3.x

pandas, numpy, matplotlib, seaborn, scikit-learn

plotly, missingno

Install all dependencies with:
pip install -r requirements.txt
🎓 References

scikit-learn: Logistic Regression

Kaggle: Telco Customer Churn Dataset

🙏 Acknowledgements

Dataset by Ahmed Gaitani

Inspired by IBM sample datasets and open-source churn prediction work
📈 GitHub Stats
<p align="center"> <a href="https://github.com/YourUsername"> <img src="https://github-readme-stats.vercel.app/api?username=YourUsername&show_icons=true&theme=radical" alt="GitHub Stats" /> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YourUsername&layout=compact&theme=radical" alt="Top Languages" /> </a> </p>
