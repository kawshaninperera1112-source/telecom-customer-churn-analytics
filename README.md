# Telecom Customer Churn & Retention Analytics with Statistical Validation

## 📌 Project Overview
This project focuses on analyzing customer churn for a telecommunications company to identify the key factors driving customer defection. It provides data-driven insights to help the business improve its customer retention strategies. The project combines interactive data visualization with rigorous statistical testing to ensure the insights are mathematically sound.

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** For Data Cleaning (Power Query), Data Modeling, DAX Measures, and Interactive Dashboard Design.
* **Python (Google Colab):** For advanced statistical analysis using `pandas` and `scipy.stats`.

---

## 📊 Key Business Insights (From Power BI)
* **Contract Type:** Customers on a **Month-to-month** contract are at the highest risk, showing a critical churn rate of **42.71%**.
* **Payment Method:** Customers using **Electronic Checks** exhibit a significantly higher churn probability compared to automated payment methods.
* **Internet Service:** **Fiber Optic** subscribers experience higher churn rates, indicating potential service or pricing dissatisfaction.

---

## 🔬 Statistical Validation (Chi-Square Test)
To prove that the relationship between a customer's **Payment Method** and **Churn** is real and not just a random coincidence, a **Chi-Square Test of Independence** was conducted in Python.

### Results:
* **Chi-Square Statistic:** 648.14
* **P-Value:** $3.68 \times 10^{-140}$

Since the **P-Value is extremely close to 0 ($p < 0.05$)**, we reject the Null Hypothesis. This **statistically proves** that the payment method is a highly significant driver of customer churn. 

---

## 💡 Business Recommendations
1. **Migrate to Auto-Pay:** Implement targeted marketing campaigns and offer financial incentives (e.g., a small monthly discount or loyalty points) to transition Electronic Check users to automatic payment methods like **Credit Card Auto-Debit** or **Bank Transfer**.
2. **Contract Incentives:** Offer special loyalty discounts for Month-to-month customers who switch to a 1-year or 2-year secure contract.

---

## 📂 How to Review the Project
* Open the `.pbix` file in Power BI Desktop to interact with the dashboard.
* Check the Python notebook or script to view the source code for the Chi-Square test validation.
