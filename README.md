# 📊 Loan Default and Financial Risk Dashboard

This Power BI dashboard project provides a comprehensive overview of **loan default patterns**, **financial risk metrics**, and **applicant demographics**. The aim is to help financial institutions understand the factors contributing to loan defaults and guide data-driven decision-making.

---

## 📌 Project Overview

The dashboard is divided into **three main sections**:

1. **Loan Default and Overview**
2. **Applicant Demographics and Financial Profile**
3. **Financial Risk Metrics**

Each section is designed to analyze key aspects of the lending process including default trends, income distribution, age & marital status impact, and credit risk segmentation.

---

## 📁 Dashboard Sections and Key Insights

### 🔹 1. Loan Default and Overview
## Screenshot 1
![screenshot1](https://github.com/kunal1300/Loan/blob/a1ade15f484bd098603553880e49b279acc0ae0f/Screenshot%201.png)

 
| Visualization | Description |
|---------------|-------------|
| **Loan Amount by Purpose** | Home loans dominate followed by Business and Education loans. |
| **Average Income by Employment Type** | Unemployed applicants have the highest average income, suggesting possible outliers or specific wealthy individuals without formal jobs. |
| **Default Rate by Year (2013–2018)** | Default peaked in 2016 (11.75%) and was lowest in 2014 and 2017 (11.5%). |
| **Average Loan by Age Group** | Adults take the highest average loan, followed by middle-aged adults. Teens have the lowest. |

---

### 🔹 2. Applicant Demographics and Financial Profile
## Screenshot 2
![screenshot2](https://github.com/kunal1300/Loan/blob/a1ade15f484bd098603553880e49b279acc0ae0f/Screenshot%202.png)
| Visualization | Description |
|---------------|-------------|
| **Average Loan by Age Group and Marital Status** | Highest average loan observed among Single and Divorced adults. Teen applicants take relatively smaller loans. |
| **Median Loan by Credit Score Bins** | As expected, applicants with **lower credit scores** tend to have **higher median loan amounts**, indicating potential risk. |
| **Loans by Employment Type vs Education** | Part-time and unemployed individuals with lower education backgrounds still secure high loan amounts. |
| **Loan Distribution by Dependents and Mortgage (Middle-aged Adults)** | Equal loan distribution regardless of dependents. |
| **Total Loan by Credit Score Bins (Adults)** | Medium and High credit score holders dominate total loan volume, but Low score group still has significant share (~1.1B). |

---

### 🔹 3. Financial Risk Metrics
## Screenshot 3
![screenshot3](https://github.com/kunal1300/Loan/blob/a1ade15f484bd098603553880e49b279acc0ae0f/Screenshot%203.png)
| Visualization | Description |
|---------------|-------------|
| **YOY Default Loan Change (2013–2018)** | Highest rise in 2015 (2.7%) and a drop in 2017 (-2.8%). |
| **YOY Loan Amount Change** | Significant growth seen in 2015 (1.3B) and 2018 (1.7B). |
| **Loan Amount by Credit Score and Marital Status (YTD)** | Balanced distribution across High and Medium bins, skewed toward Married applicants. |
| **Sankey Chart - Income to Education Flow** | High income applicants mostly opt for advanced degrees like PhDs and Master’s; lower income groups lean toward High School. |

---

## 🛠️ Tools & Technologies

- **Power BI** – Interactive data visualization
- **DAX / Power Query** – Data transformation
- **Microsoft Excel / CSV** – Data source
- **GitHub** – Version control and portfolio hosting

---

## 📈 Key Business Use Cases

- Detect **high-risk applicants** based on credit, income, and employment status.
- Plan **targeted loan marketing** to stable segments (e.g., Full-time, Adult, Married).
- Monitor **year-over-year loan default trends** for financial forecasting.
- Improve **credit scoring models** using demographic and financial attributes.

---

## 🔍 Recommendations

- Revisit loan policies for **Unemployed but high-income individuals**.
- Develop **risk-based pricing models** using credit score segmentation.
- Introduce **educational financial literacy** for younger (Teen) applicants.

---

## 📎 How to Use

1. Open the `.pbix` file in Power BI Desktop ![File](https://github.com/kunal1300/Loan/blob/a0875ba7deefa4799542705566e45622ad094eaf/Loan.pbix).
2. Interact with filters to explore dimensions like age, marital status, employment, and more.
3. Export visuals or integrate with Power BI service for web sharing.

---

## 📂 Repository Structure

```bash
📁 loan-default-dashboard
├── README.md
├── images/
│   ├── screenshot1.png
│   ├── screenshot2.png
│   └── screenshot3.png
└── Loan_Default_Analysis.pbix (optional - Power BI file)

