# Databel Customer Churn Analysis Dashboard | Power BI

## 📊 Project Overview

This project analyzes customer churn for Databel using Power BI. The dashboard provides an interactive overview of customer retention, churn reasons, customer charges, and customer service performance.

The objective is to identify the main factors contributing to customer churn and provide insights that can help improve customer retention and support business decision-making.
---------------

<img width="713" height="331" alt="Screenshot 2026-10-20 185428" src="https://github.com/user-attachments/assets/22bab8bd-172d-46a8-b36f-9480f3cc00ea" />


----------------
## 🎯 Project Objectives

- Analyze the overall customer churn rate.
- Identify the most common reasons customers leave.
- Explore churn categories and customer behavior.
- Compare customer churn across states.
- Analyze the relationship between customer service calls and churn.
- Monitor monthly charges and total customer charges.
- Support data-driven customer retention strategies.

## 🛠️ Tools & Technologies

- **Power BI** — Dashboard development and data visualization.
- **Power Query** — Data preparation and transformation.
- **DAX** — Calculated measures and KPI analysis.
- **CSV** — Source dataset.

## 📁 Dataset

The project uses the `Databel - Data.csv` dataset, containing **6,687 customer records and 29 columns**.

Key fields include:

- Customer ID and Churn Label
- Account Length
- State and Gender
- Monthly Charge and Total Charges
- Customer Service Calls
- Contract Type and Payment Method
- Customer Group Information
- Churn Category and Churn Reason
- International Plans and Data Usage

## 📈 Dashboard Features

### 1. Key Performance Indicators (KPIs)

- **Total Charges:** Approximately 7.25M
- **Average Monthly Charge:** Approximately $31
- **Churned Customers:** 1,796
- **Customer Churn Rate:** 26.86%

### 2. Top 10 Churn Reasons

A horizontal bar chart ranks the most frequently reported reasons for customer churn, including:

- Price too high
- Product dissatisfaction
- Network reliability
- Long-distance charges
- Service dissatisfaction
- Moved
- Limited range of services
- Poor online support
- Lack of self-service options
- Poor phone support

### 3. Churn by State

A geographic map provides a state-level view of churn and total customer counts to help explore differences across locations.

### 4. Customer Group Analysis

A column chart compares churned customers with the number of customers in a group, providing insight into customer group patterns.

### 5. Churn by Category

A treemap visualizes churn categories, including:

- Competitor
- Attitude
- Dissatisfaction
- Price
- Other

### 6. Customer Service Calls Analysis

A line and area chart explores churn rate by the number of customer service calls, helping highlight the relationship between repeated support interactions and customer attrition.

### 7. Interactive Churn Rate Gauge

A gauge displays the overall churn rate against a 100% scale.

### 8. Interactive Filters

Users can filter the dashboard by:

- State
- Group
- Gender

These filters help users explore customer segments and compare churn patterns.


# Databel Customer Churn Analysis | Power BI Dashboard

<p align="center">
  <img src="Databel%20Dashboard.png" alt="Databel Customer Churn Analysis Dashboard" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Data%20Analysis-Customer%20Churn-FF7F50?style=for-the-badge" alt="Customer Churn">
  <img src="https://img.shields.io/badge/Project-Portfolio-6C63FF?style=for-the-badge" alt="Portfolio Project">
</p>

## Table of Contents

- [Project Overview](#project-overview)
- [Business Objectives](#business-objectives)
- [Tools and Technologies](#tools-and-technologies)
- [Dataset Overview](#dataset-overview)
- [Dashboard KPIs](#dashboard-kpis)
- [Dashboard Visualizations](#dashboard-visualizations)
- [Customer Churn Comparisons](#customer-churn-comparisons)
- [Key Findings](#key-findings)
- [Business Recommendations](#business-recommendations)
- [Methodology](#methodology)
- [How to Run the Project](#how-to-run-the-project)
- [Repository Structure](#repository-structure)
- [Skills Demonstrated](#skills-demonstrated)

---

## Project Overview

This project presents an interactive **Customer Churn Analysis Dashboard** developed using Microsoft Power BI.

The dashboard analyzes customer data to identify churn patterns, understand why customers leave, compare customer segments, and explore the relationship between customer service interactions and churn.

It combines KPI cards, bar charts, a geographic map, a treemap, an area chart, a gauge, and interactive filters to transform raw customer data into meaningful business insights.

**Project focus:** Customer retention, churn analysis, business intelligence, and data-driven decision-making.

## Business Objectives

- Measure the overall customer churn rate.
- Identify the most common reasons for customer attrition.
- Compare churn across categories and customer groups.
- Explore churn patterns across different US states.
- Analyze churn rates according to customer service calls.
- Evaluate customer charges and revenue-related metrics.
- Provide actionable recommendations to improve customer retention.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Interactive dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and analytical measures |
| CSV | Source data format |
| Data Visualization | Communicating patterns and trends |
| Business Intelligence | Supporting data-driven decisions |

## Dataset Overview

The project uses the `Databel - Data.csv` dataset.

| Dataset Attribute | Details |
|---|---|
| Total customer records | 6,687 |
| Number of columns | 29 |
| Analysis subject | Customer churn |
| Geographic coverage | US states |
| Customer information | Gender, age, group membership |
| Financial information | Monthly Charge, Total Charges |
| Service information | Customer Service Calls, data usage, international plans |
| Churn information | Churn Label, Churn Category, Churn Reason |

### Important Dataset Fields

| Field | Description |
|---|---|
| Customer ID | Unique customer identifier |
| Churn Label | Indicates whether a customer churned |
| State | Customer's state |
| Gender | Customer gender |
| Group | Indicates group membership |
| Number of Customers in Group | Customer group size measure |
| Monthly Charge | Monthly customer charge |
| Total Charges | Total charges recorded |
| Customer Service Calls | Number of service calls |
| Churn Category | Broad classification of churn |
| Churn Reason | Reported reason for leaving |
| Contract Type | Customer contract arrangement |
| Payment Method | Customer payment method |

## Dashboard KPIs

The following KPIs summarize the supplied dataset.

| KPI | Value | Business Meaning |
|---|---:|---|
| Total Customer Records | 6,687 | Total records analyzed |
| Churned Customers | 1,796 | Customers with a churn label of Yes |
| Overall Churn Rate | 26.86% | Share of customers who churned |
| Average Monthly Charge | $31.03 | Average monthly charge per customer |
| Total Charges | $7,247,074 | Sum of the Total Charges field |

### Churn Rate Calculation

The churn rate is calculated as:

`Churn Rate = Churned Customers / Total Customers × 100`

Using the dataset:

`1,796 / 6,687 × 100 = 26.86%`

**Note:** Total Charges represents the sum of the recorded Total Charges field, not necessarily recognized revenue for a specific reporting period.

## Dashboard Visualizations

| Visualization | Analytical Purpose |
|---|---|
| KPI Cards | Summarize charges, average monthly charges, churned customers, and churn rate |
| Top 10 Churn Reasons | Rank the most frequently reported reasons for leaving |
| US Geographic Map | Explore churn rate and customer counts by state |
| Customer Group Comparison | Compare churned customers and customer group counts |
| Churn Category Treemap | Compare churn volumes across churn categories |
| Customer Service Calls Chart | Explore churn rates by number of service calls |
| Churn Rate Gauge | Display the overall churn rate against a 100% scale |
| Interactive Slicers | Filter the analysis by state, group, and gender |

## Customer Churn Comparisons

This section summarizes the main comparisons supported by the dataset and dashboard.

### 1. Comparison of Churn Categories

The table compares the number of churned customers by reported churn category.

| Churn Category | Churned Records | Share of All Churned Records |
|---|---:|---:|
| Competitor | 805 | 44.82% |
| Attitude | 287 | 15.98% |
| Dissatisfaction | 286 | 15.92% |
| Price | 200 | 11.14% |
| Other | 191 | 10.63% |
| Missing Category | 27 | 1.50% |
| **Total** | **1,796** | **100.00%** |

**Comparison insight:** Competitor-related churn is the largest category, accounting for approximately 44.82% of churned records. This suggests that competitive offers, pricing, or product differences deserve further investigation.

### 2. Comparison of the Top Individual Churn Reasons

| Rank | Churn Reason | Number of Customers |
|---:|---|---:|
| 1 | Competitor made better offer | 303 |
| 2 | Competitor had better devices | 297 |
| 3 | Attitude of support person | 203 |
| 4 | Don't know | 123 |
| 5 | Competitor offered more data | 110 |
| 6 | Competitor offered higher download speeds | 95 |
| 7 | Attitude of service provider | 84 |
| 8 | Price too high | 74 |
| 9 | Product dissatisfaction | 73 |
| 10 | Network reliability | 69 |

**Comparison insight:** The two most frequent individual churn reasons are competitor-related. Together, they account for 600 records, highlighting the importance of competitive offers and device value.

### 3. Comparison of Churn Rate by Customer Service Calls

| Number of Service Calls | Total Customers | Churned Customers | Churn Rate |
|---:|---:|---:|---:|
| 0 | 4,056 | 361 | 8.90% |
| 1 | 889 | 278 | 31.27% |
| 2 | 863 | 316 | 36.62% |
| 3 | 297 | 260 | 87.54% |
| 4 | 293 | 292 | 99.66% |
| 5 | 289 | 289 | 100.00% |

**Comparison insight:** Churn rates rise substantially across customers with more service calls. Customers with four or five calls have particularly high churn rates in this dataset.

This is an association, not proof that service calls cause churn. Customer complaints and other underlying issues may contribute to both.

### 4. Comparison of Churn by Customer Group Membership

| Group Membership | Total Customers | Churned Customers | Churn Rate |
|---|---:|---:|---:|
| Group = No | 5,166 | 1,697 | 32.85% |
| Group = Yes | 1,521 | 99 | 6.51% |

**Comparison insight:** Customers marked as group members have a substantially lower observed churn rate than customers who are not group members.

This pattern suggests a potential retention opportunity, but further analysis is needed to determine which group characteristics are associated with lower churn.

### 5. Comparison of Churn by Contract Type

| Contract Type | Total Customers | Churned Customers | Churn Rate |
|---|---:|---:|---:|
| Month-to-Month | 3,411 | 1,579 | 46.29% |
| One Year | 1,479 | 167 | 11.29% |
| Two Year | 1,797 | 50 | 2.78% |

**Comparison insight:** Month-to-month customers have a much higher observed churn rate than customers with one-year or two-year contracts.

Contract type is a useful additional comparison available in the dataset, even though it is not a separate chart in the supplied dashboard screenshot.

### 6. Comparison of Churn by Payment Method

| Payment Method | Total Customers | Churned Customers | Churn Rate |
|---|---:|---:|---:|
| Paper Check | 371 | 141 | 38.01% |
| Direct Debit | 3,702 | 1,277 | 34.49% |
| Credit Card | 2,614 | 378 | 14.46% |

**Comparison insight:** Customers using paper checks have the highest observed churn rate among the three payment methods. Payment method may be worth investigating alongside contract type, customer experience, and customer tenure.

### 7. Comparison of Churn by Gender

| Gender | Total Customers | Churned Customers | Churn Rate |
|---|---:|---:|---:|
| Female | 3,301 | 897 | 27.17% |
| Male | 3,379 | 897 | 26.55% |
| Prefer not to say | 7 | 2 | 28.57% |

**Comparison insight:** Female and male customers have similar churn rates in the dataset. The group marked "Prefer not to say" is too small to support a reliable comparison.

### 8. Geographic Comparison

The dashboard includes a geographic map to explore churn rate and total customer counts across US states.

| Geographic Measure | Purpose |
|---|---|
| Churn Rate by State | Identify locations with relatively high customer attrition |
| Customer Count by State | Understand differences in customer population |
| State Filter | Focus the dashboard on a selected state |

**Comparison insight:** State-level analysis helps identify where additional investigation may be useful. State-level differences should be interpreted alongside customer counts to avoid drawing conclusions from small samples.

## Key Findings

1. **Competitor-related churn dominates:** 805 churned records fall into the Competitor category.
2. **Competitive offers are important:** The two most frequent individual churn reasons relate to better competitor offers and devices.
3. **Service-call frequency is a strong churn indicator:** Observed churn rates increase from 8.90% for customers with no service calls to 100% for customers with five calls.
4. **Group membership is associated with lower churn:** Group members have a 6.51% churn rate compared with 32.85% for non-members.
5. **Contract type shows a substantial difference:** Month-to-month customers have a 46.29% churn rate, compared with 2.78% for two-year customers.
6. **Payment method may provide another useful segmentation:** Credit card customers have a lower observed churn rate than the other payment groups.
7. **Overall churn remains significant:** Approximately 26.86% of customer records are labeled as churned.

## Business Recommendations

Based on the observed patterns, the following actions could be investigated:

- **Competitive positioning:** Review pricing, device offers, data allowances, and download speeds against competitors.
- **Proactive customer support:** Identify customers with repeated service calls and investigate unresolved issues.
- **Retention programs:** Explore appropriate retention offers for month-to-month customers.
- **Group-based opportunities:** Investigate whether group plans or shared benefits contribute to lower churn.
- **Payment experience:** Explore whether payment friction, customer demographics, or other factors help explain differences by payment method.
- **Geographic analysis:** Prioritize further investigation in states with high churn and sufficient customer volumes.
- **Continuous monitoring:** Track churn rate and churn reasons over time to evaluate whether retention initiatives are effective.

These recommendations are hypotheses for further investigation, not proven causal conclusions.

## Methodology

The project follows a business intelligence workflow:

1. **Data understanding:** Review the available customer, financial, service, and churn fields.
2. **Data preparation:** Inspect data types, missing values, and field consistency in Power Query.
3. **KPI development:** Calculate customer counts, churned customer counts, charges, and churn rates.
4. **Comparative analysis:** Compare churn categories, churn reasons, service-call frequency, and customer segments.
5. **Visualization:** Present the results through KPI cards, charts, a map, a treemap, a gauge, and interactive slicers.
6. **Interpretation:** Translate observed patterns into potential customer retention actions.

### Analytical Definitions

| Measure | Definition |
|---|---|
| Total Customers | Count of customer records |
| Churned Customers | Count of records with Churn Label = Yes |
| Churn Rate | Churned customers divided by total customers |
| Category Share | Churned records in a category divided by all churned records |
| Segment Churn Rate | Churned customers in a segment divided by all customers in that segment |
| Average Monthly Charge | Average of the Monthly Charge field |
| Total Charges | Sum of the Total Charges field |

## How to Run the Project

### Requirements

- Microsoft Power BI Desktop
- The source dataset: `Databel - Data.csv`
- The Power BI report file (`.pbix`), if included in the repository

### Setup Instructions

1. Clone or download this repository from GitHub.
2. Open Power BI Desktop.
3. Select **Get Data → Text/CSV**.
4. Import `Databel - Data.csv`.
5. Open Power Query to inspect column types and data quality.
6. Apply changes and load the data.
7. Open the supplied `.pbix` file if available, and update the data source path if necessary.
8. Refresh the dataset to update the report.

**Note:** The CSV file contains the source data, not the interactive Power BI report itself. The `.pbix` file must be uploaded separately if you want others to open and interact with your dashboard.

## Repository Structure

```text
Databel-Customer-Churn-Analysis/
│
├── Databel - Data.csv
├── Databel Dashboard.png
├── Databel Customer Churn.pbix
└── README.md
```

The filenames above are suggested examples. Replace them with the exact filenames you upload. If you do not have the `.pbix` file available, omit it from the structure.

## Skills Demonstrated

- Data cleaning and preparation
- Power Query
- DAX and KPI calculations
- Customer churn analysis
- Comparative and segment analysis
- Data visualization
- Dashboard design
- Business insight generation
- Analytical storytelling
- Business intelligence reporting

## Project Outcome

The project transforms customer data into an interactive analytical dashboard that highlights customer churn patterns and potential retention opportunities.

It demonstrates how Power BI can be used to explore customer behavior, compare business segments, monitor KPIs, and communicate findings to support evidence-based decision-making.

---

**Project:** Databel Customer Churn Analysis  
**Technology:** Microsoft Power BI  
**Domain:** Customer Analytics and Business Intelligence


## 🚀 Project Outcome

This project demonstrates the use of Power BI to transform customer data into an interactive analytical dashboard. It showcases data visualization, KPI reporting, customer segmentation, churn analysis, and the communication of actionable business insights.

## 👩‍💻 Skills Demonstrated

Power BI | Data Analysis | Data Visualization | DAX | Power Query | KPI Development | Customer Churn Analysis | Business Intelligence

---

**Project:** Databel Customer Churn Analysis Dashboard  
**Tool:** Microsoft Power BI
