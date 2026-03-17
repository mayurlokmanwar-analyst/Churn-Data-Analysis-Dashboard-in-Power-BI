# 📉 Customer Churn & Retention Strategy Dashboard

Welcome to the **Customer Churn Analysis** repository! This project utilizes **Power BI** to perform a deep-dive analysis into customer behavior, identifying the root causes of attrition and providing a strategic roadmap to protect recurring revenue.

[📊 View Project Repository](https://github.com/mayurlokmanwar-analyst/Churn-Data-Analysis-Dashboard-in-Power-BI)

---

## 🚀 Overview
Customer churn is a critical metric for subscription-based businesses. This project maps demographics against contract types and service usage to pinpoint exactly why customers leave, allowing for targeted retention interventions.

### Key Business Questions Addressed:
- **The Bottom Line:** Current **Churn Rate** trends over the last quarter.
- **Risk Profiling:** Identifying which segments (**Age, Gender, Tenure**) are most susceptible to leaving.
- **Contractual Impact:** Measuring how **Month-to-Month vs. Long-term contracts** impact loyalty.
- **Service Correlation:** Analyzing if service gaps (like lack of Tech Support) drive higher attrition.

---

## 🛠️ Technical Toolbelt
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power_Query-0078D4?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-Advanced_Analytics-blue?style=for-the-badge)

- **Data Engineering:** Used **Power Query** for ETL, advanced data cleaning, and normalization of categorical variables.
- **Data Modeling:** Implemented a **Star Schema** with optimized Fact and Dimension tables for high-performance reporting.
- **Advanced DAX:** Developed complex measures for **Churn Rate %**, **Retention Rate**, and **Month-over-Month (MoM) Growth**.

---

## 📸 Dashboard Features
- **Executive Summary:** High-level KPIs for **Total Customers**, **Churn Count**, and **Revenue Leakage**.
- **Demographic Deep-Dive:** Churn analysis by seniority, partner status, and dependents.
- **Account Analysis:** Correlation between **Payment Methods**, **Paperless Billing**, and tenure.
- **Risk Assessment Matrix:** Identifies **"At-Risk"** customers based on low tenure and high charges.

---

## 💡 Strategic Business Insights
* **The "Month-to-Month" Trap:** Short-term contracts represent the **highest churn risk**, contributing to nearly **60% of total attrition**.
* **The Critical Window:** A significant **"Early Churn"** trend occurs within the first **6 months** of the customer lifecycle.
* **Value-Added Services:** Customers without **Online Security** or **Tech Support** churn at a **20% higher rate**, suggesting a need for service bundling.

---

## 📁 Project Structure
```text
Customer-Churn-Analysis/
├── Data/               # Source subscriber transaction history
├── Screenshots/        # High-resolution Executive and Risk Analysis views
├── Churn Data Analytics.pbix # Core Power BI Interactive Dashboard
└── README.md           # Project Documentation
