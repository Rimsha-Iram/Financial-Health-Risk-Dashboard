# 💰 Financial Health & Risk Dashboard (Power BI)

## 📌 Project Overview
This Power BI project provides a **comprehensive financial health and risk assessment** of 15,000 applicants using key financial indicators such as income, credit score, debt ratio, and loan performance.  
The dashboard was designed to help businesses and financial institutions identify **low, medium, and high-risk individuals**, evaluate financial stability, and support **data-driven lending and investment decisions**.

---
## 🖼️ Dashboard Preview

### 📊 Financial Health & Risk Dashboard - Overview
![Dashboard Overview](https://github.com/yourusername/yourrepo/assets/12345678/abcd1234efgh)

### 💡 Financial Health & Risk Dashboard - Risk Analysis
![Dashboard Risk Analysis](https://github.com/yourusername/yourrepo/assets/12345678/ijkl5678mnop)

---

## 🧾 Dataset Details
**Dataset Name:** Financial Risk Assessment  
**Source:** Kaggle  
**File Type:** CSV  

### **Columns Overview**
| Column | Description |
|--------|--------------|
| Age | Applicant’s age |
| Gender | Gender identity of applicant |
| Education Level | Education qualification |
| Marital Status | Marital status of the applicant |
| Income | Total income of the applicant |
| Credit Score | Creditworthiness measure (300–850 scale) |
| Loan Amount | Total loan requested |
| Loan Purpose | Reason for taking the loan |
| Employment Status | Job type or employment condition |
| Years at Current Job | Work experience in years |
| Payment History | Record of loan repayments |
| Debt-to-Income Ratio | Debt relative to income |
| Assets Value | Total value of assets owned |
| Number of Dependents | Financial dependents count |
| City / State / Country | Location details |
| Previous Defaults | Count of past loan defaults |
| Marital Status Change | Whether marital status recently changed |
| Risk Rating | Financial risk category (Low / Medium / High) |

---

## ⚙️ Data Cleaning & Transformation
Performed in **Power Query (Power BI)**:
- Removed duplicates and null-heavy records.
- Standardized column types (numeric/date/text).
- Created calculated columns:
  - **Savings** = Income – Expenses (optional)
  - **Debt_Income_Ratio** = Debt ÷ Income (already included)
  - **Age_Group** (e.g., 18–25, 26–35, etc.)
- Built DAX measures for KPIs:
  - `Avg Income = AVERAGE(financial_risk_assessment[Income])`
  - `Avg Credit Score = AVERAGE(financial_risk_assessment[Credit Score])`
  - `Avg Debt Ratio = AVERAGE(financial_risk_assessment[Debt-to-Income Ratio])`
  - `Total Applicants = COUNTROWS(financial_risk_assessment)`

---

## 📊 Dashboard Sections

### **1️⃣ KPI Overview**
- **Total Applicants:** 15K  
- **Average Income:** 69.93K  
- **Average Credit Score:** 699.11  
- **Average Debt Ratio:** 0.35  

### **2️⃣ Demographics**
- **Bar Chart:** Average Income by Age Group → shows 56+ age group earning the highest.  
- **Donut Chart:** Gender distribution balanced across Male, Female, Non-binary.  
- **Heat Map:** Income distribution by country → top income from Korea & Congo.

### **3️⃣ Financial Insights**
- **Column Chart:** Credit Score by Education → higher education = better credit.  
- **Line Chart:** Credit Score by Age → older applicants have higher scores.  
- **Scatter Plot (optional):** Debt Ratio vs Income colored by Risk Rating.

### **4️⃣ Risk Analysis**
- **Donut Chart:** Risk Rating Distribution → 60% Low, 30% Medium, 10% High.  
- **Clustered Bar Chart:** Loan Amount by Risk Rating → higher loans for low-risk applicants.  
- **Card Visual:** Total count of High-Risk individuals.

### **5️⃣ Interactive Filters (Slicers)**
- Education Level  
- Employment Status  
- Risk Rating  
- Gender  
- Age Group  

---

## 📈 Analytical Findings
- 56+ age group shows **highest total income (≈234M)**.  
- **Average Credit Score (699)** reflects a financially stable dataset.  
- **Debt-to-Income Ratio (0.35)** indicates manageable debt levels.  
- **PhD & Master’s degree holders** maintain stronger credit scores.  
- **Younger groups** tend to have weaker credit profiles.  
- **Majority of applicants (60%)** fall into **low-risk** category.  

---

## 💡 Insights
- **Education level** positively influences credit health and risk rating.  
- **Age and financial maturity** improve overall financial stability.  
- Balanced gender ratio implies unbiased financial opportunities.  
- **Country-level differences** highlight income concentration in a few regions.

---

## 🧭 Recommendations
1. **Financial Literacy Programs:** Target younger and less educated applicants.  
2. **Lending Strategy:** Prioritize low-risk clients; stricter terms for high-risk ones.  
3. **Age-based Offers:** Develop senior-focused investment and insurance products.  
4. **Regional Focus:** Expand services in countries with higher income potential.  
5. **Ongoing Monitoring:** Regularly track debt-to-income ratio and credit score trends.

---

## 🧰 Tools Used
- **Power BI Desktop**
- **Microsoft Excel (for initial inspection)**
- **DAX & Power Query**
- **Kaggle Dataset**

---

## 📢 Key Takeaway
This dashboard acts as a **data-driven decision tool** to assess financial health, lending risk, and demographic insights.  
It empowers financial teams to identify **high-risk clients early**, **optimize loan allocation**, and **strengthen credit policies** using visual analytics.

---

### 👩‍💻 Created by:
**Rimsha Iram**  
_Data Analyst | Power BI | Python | Excel | SQL_  
📩 [Portfolio Link](https://www.datascienceportfol.io/rimshairamanalytics)]  
