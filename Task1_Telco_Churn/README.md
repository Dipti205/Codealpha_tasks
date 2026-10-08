# 📉 Task 1: Telco Customer Churn Analysis

## 🎯 Objective
Understand why customers leave a telecom service and identify the factors associated with churn.

## 📂 Dataset
- 👥 7,043 customer records, 21 attributes
- 📄 File: `Customer churn.csv`

## 🧹 Data Cleaning
- ✅ Checked for missing values and duplicate customer IDs
- 🔢 Converted `TotalCharges` from string to numeric (blanks replaced with 0)
- 🔄 Converted `SeniorCitizen` from 0/1 to No/Yes

## 📊 Key Statistics
| Metric | Value |
|---|---|
| 👥 Total customers | 7,043 |
| ⏳ Avg / median tenure | 32.37 / 29 months |
| 💵 Avg / median monthly charges | 64.76 / 70.35 |
| 💰 Avg / median total charges | 2,279.73 / 1,394.55 |
| 🚪 Churn rate (per notebook) | 23.54% |

## 🔍 Key Findings
- ⏳ **Tenure:** Customers in their first 1-2 months churn the most
- 📝 **Contract:** Month-to-month customers show the highest churn
- 🛠️ **Services:** Customers without OnlineBackup or TechSupport churn notably more
- 💳 **Payment:** Electronic check is associated with higher churn
- 🚻 **Gender:** No real difference between male and female customers
- 👴 **Senior citizens:** Slightly higher churn

## 💡 Recommendations
1. 🤝 Improve onboarding in the first few months
2. 🎁 Offer loyalty benefits to month-to-month customers
3. ☁️ Promote OnlineBackup and TechSupport
4. 💳 Review the electronic-check payment experience

## 🧰 Tools Used
🐍 Python | 🐼 Pandas | 📈 Matplotlib / Seaborn | 📓 Jupyter Notebook

## 📁 Files
- 📓 `TCA.ipynb`: full analysis notebook
- 📄 `Customer churn.csv`: dataset

## ✨ Conclusion
Tenure, contract type, service usage, and payment method are the key factors linked to churn. These insights can help businesses build better customer retention strategies.
