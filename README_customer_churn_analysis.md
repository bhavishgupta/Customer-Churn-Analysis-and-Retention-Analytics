# 📊 Customer Churn Analysis & Retention Intelligence Dashboard

Telecom companies lose significant revenue to customer churn. This project analyzes churn behavior across **7,043 customers** using SQL for data extraction and transformation, and Power BI for interactive dashboard development. The objective is to identify high-risk customer segments and surface actionable retention strategies. Technologies used include **SQL Server**, **Power BI Desktop**, **Power Query (M)**, and **DAX**. The dashboard enables business stakeholders to reduce churn-driven revenue loss through data-driven decision-making.

---

## 📸 Dashboard Preview

![Dashboard Screenshot](dashboard_screenshot.png)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| SQL Server | Data extraction, cleaning, staging-to-production pipeline |
| Power BI Desktop | Dashboard development & visualization |
| Power Query (M) | Data transformation & ETL |
| DAX | KPI measures, calculated columns, time intelligence |
| Data Modeling | Star schema — fact & dimension tables |

---

## 📌 Key KPIs

- **Total Customers** — Total active customer base across all segments (7,043)
- **Total Churned Customers** — Count of customers who have discontinued service (1,869)
- **Churn Rate %** — Percentage of customers lost out of total customer base (26.5%)
- **Churned Revenue** — Monthly revenue lost due to churned customers
- **Avg Monthly Charges (Churned)** — Average billing amount for customers who churned

---

## 🔍 Key Insights

- The company has **7,043 customers**, of which **1,869 have churned**, resulting in an overall churn rate of **26.5%**.
- **Month-to-Month contract** customers account for the majority of churn, indicating significantly higher retention risk compared to one- and two-year contract holders.
- Customers using **Fiber Optic internet services** exhibit disproportionately higher churn than DSL users, suggesting unmet service quality expectations at a premium price point.
- **Senior citizens** demonstrate a higher propensity to churn than non-senior customers, representing an underserved segment requiring targeted retention efforts.
- Customers in their **first 0–12 months** of tenure represent the highest churn risk — early engagement programs are critical to improving long-term retention.
- Customers paying via **electronic check** churn at a higher rate than those using auto-payment methods, suggesting friction in the billing experience drives attrition.
- High monthly charge customers (above average billing) account for a **disproportionate share of revenue attrition**, making them a priority segment for proactive retention outreach.

---

## ⚙️ Dashboard Features

- **Interactive slicers** — filter by contract type, internet service, payment method, and tenure group
- **Drill-down analysis** — explore churn by customer demographics and service subscriptions
- **Dynamic KPI cards** — real-time churn rate, churned revenue, and customer count
- **Customer segmentation** — high-risk vs. low-risk cohort identification
- **Trend analysis** — churn patterns across tenure bands
- **Cross-filtering visuals** — linked charts update dynamically on selection

---

## 🔗 Live Dashboard

🔗 [View Power BI Dashboard](paste-your-link-here)

---

## ✅ Conclusion

This project addressed a core business problem: identifying which customer segments are most likely to churn and why. Analysis revealed that contract type, payment method, and early tenure are the strongest churn predictors. The interactive Power BI dashboard equips retention teams and business decision-makers to prioritize high-risk cohorts, design targeted intervention strategies, and ultimately reduce revenue attrition — all without requiring technical expertise to navigate the data.
