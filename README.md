# 🏦 Bank Loan Analytics Dashboard | Power BI

## 📌 Project Overview

The **Bank Loan Analytics Dashboard** is an interactive business intelligence project developed using Microsoft Power BI to analyze bank loan applications, funded amounts, repayments, loan performance, and credit risk indicators.

The dashboard provides insights into lending activities through interactive visualizations and key performance indicators (KPIs). It helps users understand loan trends, evaluate good and bad loan performance, and explore customer borrowing patterns.

## 🎯 Project Objectives

- Analyze overall bank loan application performance.
- Track total funded amounts and repayments received.
- Compare good loans and bad loans.
- Monitor average interest rates and debt-to-income (DTI) ratios.
- Identify monthly trends in loan applications.
- Analyze loans by state, purpose, term, and homeownership.
- Present key business insights through an interactive dashboard.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and data visualization
- **Power Query** — Data cleaning and transformation
- **DAX (Data Analysis Expressions)** — Measures and KPI calculations
- **Data Analytics** — Loan performance and risk analysis

## 📊 Dashboard Features

### 1. Executive Dashboard

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income (DTI) Ratio
- Monthly Loan Application Trends
- Loan Applications by State
- Loan Distribution by Term
- Loan Applications by Homeownership
- Loan Applications by Purpose

### 2. Loan Performance & Risk Analysis

- Good Loan vs. Bad Loan Analysis
- Good and Bad Loan Application Counts
- Funded Amount and Amount Received by Loan Quality
- Loan Status Analysis:
  - Fully Paid
  - Charged Off
  - Current
- Average Interest Rate by Loan Status
- Average DTI Ratio by Loan Status
- Funded Amount vs. Repayments Comparison

## 📈 Key Performance Indicators (KPIs)

The dashboard displays the following metrics from the project dataset:

| KPI | Displayed Value |
|---|---:|
| Total Loan Applications | 38,576 |
| Total Funded Amount | 435.8M |
| Total Amount Received | 473.1M |
| Average Interest Rate | 12.05% |
| Average DTI Ratio | 13.33% |

*Note: These figures reflect the dashboard screenshots. Currency units and the underlying dataset should be verified before interpreting or publishing financial conclusions.*

## 🎨 Dashboard Design

The dashboard uses a **navy-blue and gold color theme** to create a professional banking and financial analytics interface.

Key design elements include:
- KPI cards for quick performance monitoring
- Donut charts for loan quality analysis
- Bar charts for loan status and financial comparisons
- Line chart for monthly application trends
- Geographic visualization for state-wise loan applications
- Treemap for loan purpose distribution
- Interactive navigation between dashboard pages
- Filters for exploring loan categories

## 💡 Business Value

This project demonstrates how business intelligence tools can help transform raw loan data into meaningful insights.

It supports analysis of:
- Lending volume and funding activity
- Repayment performance
- Loan quality and potential credit risk
- Borrower characteristics and loan purposes
- Interest rates and debt-to-income indicators
- Trends that may support further investigation by lending teams

The dashboard is intended for analytical and educational purposes and does not independently determine borrower creditworthiness.

## 📷 Dashboard Preview

### Executive Dashboard

![Bank Loan Analytics Dashboard](screenshots/dashboard.png)

### Loan Overview Dashboard

![Bank Loan Analytics Overview](screenshots/overview.png)

*To display these previews on GitHub, upload your dashboard screenshots into a folder named `screenshots` and use the same filenames shown above.*

## 📂 Project Structure

```text
Bank-Loan-Analytics-PowerBI/
│
├── README.md
├── Bank_Loan_Analytics.pbix
├── dataset/
│   └── bank_loan_data.csv
└── screenshots/
    ├── dashboard.png
    └── overview.png
```

*This is a suggested structure. Adjust the filenames and folders to match the files included in your repository.*

## 🚀 How to Use the Project

1. Clone or download this repository.
2. Download and install Microsoft Power BI Desktop.
3. Open the `.pbix` file in Power BI Desktop.
4. If required, update the dataset path in the data source settings.
5. Refresh the data and review the dashboard pages.
6. Use the available filters and navigation controls to explore the analysis.

## 🔍 Future Improvements

- Add year-over-year and month-over-month comparisons.
- Develop more detailed borrower segmentation.
- Introduce additional risk indicators and repayment trend analysis.
- Improve data validation and automated refresh workflows.
- Add further drill-through pages for detailed loan analysis.

## 👨‍💻 Author

**Hardik Kumar Singh**

| Aspiring Data Analyst

Interested in Power BI, SQL, Excel, business intelligence, and data-driven decision-making.

### Snapshots 
DashBoard. https://github.com/Hardixkk/Bank-Loan-Analytics-Dashboard/blob/main/Dashboard%20Bank%20Loan%20Analytics.png


## ⭐ Acknowledgements

This project was created as a practical data analytics project to develop skills in dashboard design, data visualization, KPI reporting, and business intelligence using Microsoft Power BI.

---

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Disclaimer:** This dashboard is intended for educational and portfolio demonstration purposes. The accuracy of its findings depends on the underlying dataset and calculation logic.
