# 📊 Home Credit Indonesia – Credit Risk Scorecard  
## 🏆 Virtual Internship Experience – Data Scientist  
**Author: Riska Amylatul Askiyah**

---

## 📌 Overview  
This project was completed as part of the **Virtual Internship Experience by Rakamin x Home Credit Indonesia** for the **Data Scientist** role.

The goal of this project is to build a **Credit Risk Scorecard Model** that predicts customers’ loan repayment ability using historical data. The workflow includes **problem research, data preparation, exploratory data analysis (EDA), modeling**, and **business recommendations** that help support better credit decisions.

📁 **Complete Project Documentation:**  
👉 https://github.com/riskaamylatulaskiyah/Home-Credit-Indonesia-ScoreCard

---

# 🏢 Project Background  
PT Home Credit Indonesia is a financing company that provides cash loans and online/offline installment financing. One of the biggest business challenges is accurately assessing **clients’ repayment capability**, ensuring that:

- Eligible clients are **not wrongly rejected**, and  
- The company minimizes **non-performing loans**.

To achieve this, a predictive model is needed to identify clients who are likely to experience repayment difficulties.

---

# 🎯 Objectives  
1. Identify client characteristics associated with repayment difficulties.  
2. Predict client repayment ability using machine learning models.

---

# 🛠 Methodology  
The project workflow includes:

1. **Data Preparation & EDA**  
2. **Data Cleaning & Preprocessing**  
3. **Machine Learning Model Development**  
4. **Business Recommendations**

---

# 📂 Data Source  
Two datasets from Home Credit:

- `application_train.csv` → contains target variable (`TARGET`)  
- `application_test.csv` → without target variable  

These datasets represent the main application data used for credit scoring.

---

# 🧩 Challenges  
- Large dataset size  
- Imbalanced target variable  
- Missing values  
- Outliers in several features  

---

# 🧹 Data Preprocessing  
Key preprocessing steps:

- Missing value handling  
- Outlier removal using IQR  
- Feature encoding (label & one-hot encoding)  
- Feature scaling  
- Balancing data using **SMOTE**  

---

# 🔍 Business Insights (EDA)

### 📌 Age Distribution  
- Most applicants are between **25–60 years old**.  
- Highest application volume from **35–40 years old**.  
- Age **35–45** shows the most reliable repayment performance.  
- Age **25–35** tends to have higher repayment difficulty.

---

### 📌 Employment Type  
- **Students:** 100% successful repayment for both cash & revolving loans, though only 0.005% of total applicants.  
- **Accountants, Highly Skilled Technical Staff, Managers:** Strong repayment performance (95% approved), but low number of applicants.

---

### 📌 Income Type + Loan Type  
- **Maternity Leave + Cash Loan:** 100% repayment difficulty  
- **Maternity Leave + Revolving Loan:** 100% successful repayment  
- **Unemployed + Cash Loan:** >50% repayment difficulty  
- **Unemployed + Revolving Loan:** 100% successful repayment  

Loan product selection significantly affects repayment outcomes.

---

# 🤖 Machine Learning Models  

Trained models:

- Logistic Regression  
- KNN  
- Decision Tree  
- **Random Forest (Best Model)**  

### 📌 Model Evaluation  
The **Random Forest Classifier** was selected as the best-performing model due to:

- Stable accuracy between train & test datasets  
- No underfitting or overfitting  
- Strong performance with high-dimensional and imbalanced data  

---

# 💡 Business Recommendations  

### 1️⃣ Target reliable customer segments  
Focus marketing and offers on ages **35–45**, who demonstrate the highest repayment consistency.

### 2️⃣ Adjust product offerings for high-risk groups  
- Avoid **cash loans** for maternity leave and unemployed clients.  
- Recommend **revolving loans**, which show significantly better repayment outcomes.

### 3️⃣ Increase acquisition of high-quality applicant profiles  
Encourage more applications from students, accountants, skilled technical workers, and managers.

### 4️⃣ Integrate the Scorecard Model  
Implement the **Random Forest** model into the credit approval workflow to support automated risk assessment.

---

# 📎 Repository  
All scripts, notebooks, and documentation are available here:

👉 https://github.com/riskaamylatulaskiyah/Home-Credit-Indonesia-ScoreCard

---

# 🙌 Author  
**Riska Amylatul Askiyah**  
Virtual Internship Experience – Data Scientist  
Home Credit Indonesia x Rakamin Academy
