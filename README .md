# 💳 Loan Portfolio Analysis | Power BI Dashboard

<p align="center">
  <img src="screenshots/overview.png" alt="Loan Portfolio — Power BI dashboard overview" width="100%">
</p>

<p align="center">
  <strong>Explore loan issuance, branch performance, product trends, and refusal reasons through an interactive Power BI report.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Data-Modeling-6F42C1" alt="Data Modeling">
  <img src="https://img.shields.io/badge/Loan%20Records-10%2C000-1682CB" alt="10,000 loans">
</p>

---

## 📌 Project Overview

This project uses **Power BI** to explore a loan portfolio across customers, branches, loan products, and time. The dashboard turns loan records into easy-to-read business indicators, allowing users to compare **issued vs. refused loans**, study **refusal reasons**, and analyze **loan volumes by product, branch, and governorate**.

## 🎯 Objectives

- Track overall loan portfolio activity using clear KPIs.
- Explore **issued and refused** loans and common refusal reasons.
- Compare loan volumes across **branches, governorates, and loan products**.
- Examine **monthly and yearly** loan trends.
- Build a connected data model for exploring related loan information.
- Make insights easier to explore through interactive filters and visuals.

## 🧰 Tools & Skills Used

- **Power BI Desktop** — interactive report pages, KPI cards, charts, and slicers
- **Power BI Data Modeling** — table relationships across loan-related entities
- **Data Visualization & Analysis** — comparisons by status, time, product, and location

## 🔎 Key Metrics & Insights

| Metric | Value |
|:--|--:|
| Total loans | **10,000** |
| Issued loans | **8,520 (85.2%)** |
| Refused loans | **1,480 (14.8%)** |
| Customers shown on dashboard | **~8K** |
| Branches shown on dashboard | **20** |
| Average loan amount shown on dashboard | **505.81K** |

**Observations from the dashboard:**

- The **issued** category accounts for most recorded loans (**85.2%**).
- The report compares refusal reasons including **customer ignore, blacklist, low income, bad score, and missing documents**.
- Branch, governorate, and year slicers support targeted views of loan activity.
- Product-level charts enable comparisons of loan counts and the loan mix across branches.

> KPI card values represent what is visible in the supplied dashboard screenshots; interactive filters may change the displayed results.

## 📊 Dashboard Features

### 1️⃣ Loan Business Overview

- KPI cards for total customers, loans, branches, and average loan amount
- Loan counts by **governorate**
- **Issued vs. refused** loan distribution
- Counts by **refusal reason**
- Loan trends by **month and year**
- Filters for **branch, governorate, and year**

![Loan business overview](screenshots/overview.png)

### 2️⃣ Loan Product & Branch Analysis

- Loan volume by **loan product**
- Loan count and share by **year and product**
- Product distribution across different **branches**

![Loan product and branch analysis](screenshots/analysis.png)

## 🧩 Data Model

The report connects **five tables**:

| Table | Description |
|:--|:--|
| `loans` | Core loan records, including status, product, amount, and relevant dates |
| `customers` | Customer information |
| `branches` | Branch information |
| `installments` | Installment information associated with loans |
| `transactions` | Transaction records associated with loans |

The `loans` table connects to the related tables through relationships, making it possible to analyze loan activity across multiple dimensions.

![Power BI data model showing five related tables](screenshots/data-model.png)

## ▶️ How to Open the Project

1. Download the Power BI `.pbix` report file from this repository, **once uploaded**.
2. Open it using **Power BI Desktop**.
3. If prompted for source files, update the data source paths and refresh the model.
4. Use the report pages and slicers to explore the analysis.

## 📂 Repository Structure

```text
Loan-Portfolio-PowerBI/
├── README.md
├── Loan_Portfolio_Dashboard.pbix   # Add your Power BI file
└── screenshots/
    ├── overview.png
    ├── analysis.png
    └── data-model.png
```

> **Data privacy:** Only add raw datasets if you have permission to publish them, and remove sensitive or personally identifiable information before uploading.

## ✅ Conclusion

This project demonstrates practical experience in **Power BI reporting, relational data modeling, KPI tracking, and exploratory business analysis**. It offers a structured way to understand loan portfolio performance and investigate differences across locations, products, and time.
