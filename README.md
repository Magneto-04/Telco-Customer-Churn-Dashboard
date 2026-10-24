# Telco Customer Churn Dashboard (Power BI)

An interactive Power BI dashboard analyzing customer churn patterns using the public IBM Telco Customer Churn dataset — built to identify which customer segments and behaviors are most associated with churn, surfacing insights a business could act on to improve retention.

## What it does
- Visualizes churn across 7,000+ customer records with dynamic KPI cards: Total Customers, Sum of Churn Value, Sum of Churn Score
- Includes an interactive Gender slicer to filter all visuals by customer demographic
- Breaks down churn by **Contract type** (Month-to-month, One year, Two year)
- Breaks down churn by **Internet Service type** (Fiber optic, DSL, No internet)
- Breaks down churn by **Payment Method** (Electronic check, Mailed check, Bank transfer, Credit card)

## Tech stack
- **Tool:** Power BI (Power BI Desktop)
- **Dataset:** IBM Telco Customer Churn (public dataset)
- **Visuals used:** KPI/Card visuals, Pie chart, Bar chart, Donut chart, Slicer

## Key findings
- **73.46%** of customers in the dataset did not churn; **26.54%** did.
- **Month-to-month contracts** show dramatically higher churn value than One-year or Two-year contracts — customers on flexible, no-commitment plans are far more likely to leave.
- **Fiber optic internet users** churn at a noticeably higher rate than DSL users, suggesting possible service/pricing dissatisfaction worth investigating further.
- **Electronic check** is the dominant payment method among churned customers (57.3%), compared to mailed check, bank transfer, and credit card — a potential signal worth cross-referencing with customer engagement or automation of payment methods.

## How to view
```
1. Download and install Power BI Desktop (free): https://powerbi.microsoft.com/desktop/
2. Open TelcoChurnDashboard.pbix in this repo
3. All visuals are interactive — click the Gender slicer or hover over charts to filter/explore
```
