# 🧾 Personal Finance Expense Trend Analysis using EDA (Python)

### 📊 Overview
This project analyzes **personal expense data** from **January 2025 to November 2025** using **Exploratory Data Analysis (EDA)** techniques in Python.  
It identifies **spending trends**, **category-wise patterns**, and **preferred payment modes** — helping in **financial awareness, budgeting, and decision-making**.

---

## 🎯 Objectives
- Understand **monthly spending patterns** and detect peak expense periods  
- Evaluate **spending distribution** across categories (Food, Rent, Travel, etc.)  
- Identify the **most frequently used payment modes**  
- Derive **actionable insights** to improve savings and financial planning  

---

## 📁 Dataset Information
**File Name:** `personal_expense_data.csv`  
**Duration:** 1 Jan 2025 → 6 Nov 2025  
**Total Records:** ~3000 (daily-level data)  

| Column Name | Description | Example |
|--------------|-------------|----------|
| Date | Transaction date | 2025-05-12 |
| Category | Expense type | Food, Rent, Utilities, Shopping |
| Amount | Transaction amount (₹) | 450 |
| Payment_Mode | Mode of payment | UPI, Cash, Debit Card |
| Month | Derived field from Date | May-2025 |

---

## 🧠 EDA Workflow
### **Step 1. Data Loading & Cleaning**
- Imported dataset using Pandas  
- Removed nulls, stripped column names, converted `Date` to datetime  

### **Step 2. Feature Engineering**
- Extracted **Month** and **Year** from `Date` for trend analysis  

### **Step 3. Descriptive Statistics**
- Generated summary stats (`mean`, `median`, `std`) for Amount  
- Calculated monthly and category-wise totals  

### **Step 4. Visualizations**
Created insightful charts using **Matplotlib** and **Seaborn**:
- 📈 **Monthly Spending Trend**
- 🧾 **Category-wise Spending Bar Chart**
- 💳 **Payment Mode Distribution Pie Chart**
- 🥇 **Top 3 Spending Categories**

### **Step 5. Insights**
| Insight | Finding |
|----------|----------|
| Highest Spending Month | 📅 July 2025 |
| Most Used Payment Mode | 💳 UPI |
| Top 3 Expense Categories | 🏠 Rent, 🍲 Food, 🧾 Utilities |
| Key Observation | Spending peaks during mid-year; essential expenses dominate overall budget. |

---

## 📊 Key Visuals
*(Add screenshots of your charts here once generated — optional)*  
Example visuals:  
- `monthly_spending_trend.png`  
- `category_spend_distribution.png`  
- `payment_mode_pie.png`

---

## 🧩 Tools & Libraries Used
| Tool / Library | Purpose |
|-----------------|----------|
| **Python (3.x)** | Core analysis |
| **Pandas** | Data cleaning & aggregation |
| **Matplotlib** | Visualization |
| **Seaborn** | Advanced visuals |
| **Jupyter Notebook** | EDA execution |

---

## 🧮 Insights Summary
- Spending is **consistent but peaks during certain months** — possibly due to seasonal or one-time purchases.
- **UPI payments** dominate, indicating digital-first behavior.
- **Essentials** (Food, Rent, Utilities) make up the majority of the expenses.
- Tracking trends monthly provides **clarity and better saving control**.

---

## 💡 Conclusion
This EDA highlights how structured expense tracking can transform personal finance management.  
By visualizing trends, one can make **data-driven budgeting decisions** and **optimize savings goals**.

Future improvements:
- Add **Power BI dashboard** for interactive visualization  
- Implement **forecasting models** to predict monthly spend  
- Integrate **real-time expense tracker** via APIs

---

## 👨‍💻 Author
**Satyam Singh**  
*Data Analyst | Data Engineer Enthusiast | Finance & EDA Projects*  
📧 Email: [your_email@example.com]  
🌐 GitHub: [https://github.com/yourusername](https://github.com/yourusername)  
💼 LinkedIn: [https://linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---

### ⭐ If you like this project, consider giving it a star on GitHub!
