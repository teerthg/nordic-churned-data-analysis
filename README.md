# Nordic Subscription Churn Analysis

This project analyzes customer churn behavior in subscription services across the Nordic region. It applies statistical techniques to evaluate the influence of demographics, plan type, and spending behavior on churn rates.

---

## 📊 Dataset Overview

- **CustomerID**: Unique ID for each customer
- **Country**: Country of residence (Sweden, Denmark, Norway, Finland)
- **Age**: Customer's age
- **Gender**: Male / Female
- **SubscriptionPlan**: Type of plan (Basic, Premium, Family)
- **MonthlySpend_SEK**: Monthly subscription fee in SEK
- **TenureMonths**: How long the customer has stayed (in months)
- **Churned**: 1 = Left the service, 0 = Still active

---

## 🧠 Project Objectives

- Understand churn rate patterns by country, age, and gender
- Explore how plan type and monthly spend affect retention
- Visualize customer tenure vs churn status
- Apply statistical inference to derive meaningful insights

---

## 🧪 Statistical Techniques Used

- Descriptive Statistics
- T-tests (gender vs tenure/spend)
- Correlation Analysis
- Logistic Regression
- Survival Analysis (optional)

---

## 📁 Folder Structure

```
📂 nordic-churned-analysis/
├── Nordic_Churn_Analysis.ipynb
├── nordic_churn_customers.xlsx
├── visuals/
│   ├── churn_by_country.png
│   ├── spend_vs_tenure.png
├── README.md
```

---


## 📌 Insights Preview

- Norway had the **highest churn rate** among the four countries
- Customers with **shorter tenure and lower spend** are more likely to churn
- **Basic plan holders** churn more often than Premium or Family users
- Logistic regression shows **tenure** and **monthly spend** as strongest retention indicators

---

## 👤 Author

**Teerth Gupta**  
M.Sc. Statistics & Data Science, Uppsala University

---

## Contact Information:
- Email: teerth.gupta@example.com
- LinkedIn: [Teerth Gupta](https://www.linkedin.com/in/teerthgupta/)
