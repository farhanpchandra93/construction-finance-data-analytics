# Construction Finance Data Analytics
An end-to-end data analytics project combining **construction domain knowledge, financial risk analysis, and data analytics** to explore loan portfolio performance and develop an interactive decision-support dashboard.
The project covers the complete analytical workflow from raw loan data, exploratory analysis, risk segmentation, and data preparation to an interactive **Power BI dashboard**.

## Project Background
Construction and infrastructure projects are highly dependent on access to financing and effective financial risk management.
This project explores lending data from the **Prosper Loan Dataset** and applies data analytics techniques to identify borrower characteristics, portfolio patterns, credit risk indicators, and financing opportunities.
The project was developed by combining three areas of domain knowledge:

- **Civil Engineering & Construction Management**
- **Banking & Credit Analysis**
- **Data Analytics & Business Intelligence**

## Objectives
The project aims to:
- Analyze borrower and loan portfolio characteristics.
- Identify patterns associated with loan performance and credit risk.
- Perform exploratory data analysis and borrower segmentation.
- Transform raw loan data into dashboard-ready analytical data.
- Develop risk indicators and portfolio classifications.
- Build an interactive Power BI dashboard for decision support.
- Translate analytical findings into actionable business insights.

## Project Workflow

```text
Prosper Loan Dataset
        ↓
Data Understanding
        ↓
Data Cleaning & Preparation
        ↓
Exploratory Data Analysis
        ↓
Financial & Credit Risk Analysis
        ↓
Risk Classification
        ↓
Dashboard Dataset
        ↓
Power BI Dashboard
        ↓
Business Insights
```

## Repository Structure

```text
construction-finance-data-analytics/
│
├── data/
│   ├── prosperLoanData.csv
│   └── dashboard_dataset (2).csv
│
├── notebooks/
│   └── Construction Finance Analysis Notebook.ipynb
│
├── dashboard/
│   └── Project-PS 23-Farhan Prima Chandra, S.T., M.T.pbix
│
├── presentation/
│   └── Project Presentation
│
├── images/
│   ├── bnsp_data_analyst_certificate.jpg
│   └── dqlab_data_analyst_certificate.jpg
│
├── .gitattributes
├── .gitignore
└── README.md
```

## Data Pipeline
Two main datasets are included in the analytical workflow.

### Raw Dataset

`prosperLoanData.csv`

The original Prosper loan dataset used as the primary source for data exploration, preprocessing, and financial analysis.

### Dashboard Dataset

`dashboard_dataset (2).csv`

A processed analytical dataset generated from the original data and prepared specifically for visualization and portfolio analysis in Power BI.
The transformation process includes selected financial variables and additional risk-related features used in the dashboard.

## Analysis

The notebook covers several stages of the data analytics process, including:

- Data understanding
- Data quality assessment
- Missing-value analysis
- Exploratory data analysis
- Borrower profiling
- Loan portfolio analysis
- Financial variable analysis
- Credit risk analysis
- Feature preparation
- Dashboard data preparation

## Credit Risk Analytics
The project extends descriptive analytics by introducing risk-oriented variables for portfolio monitoring.
The dashboard dataset includes derived indicators such as:

- **Loan Risk**
- **Kolektibilitas**
- **Risk Category**

These variables help translate raw lending information into more interpretable portfolio risk segments.

## Power BI Dashboard
The Power BI dashboard provides an interactive view of the lending portfolio and enables exploration of key financial and borrower characteristics.
The dashboard is designed to support:

- Portfolio monitoring
- Borrower profiling
- Credit risk assessment
- Financing analysis
- Identification of portfolio patterns and opportunities
  
The complete `.pbix` file is available in the `dashboard/` directory.

## Domain Integration
A key characteristic of this project is the integration of three professional domains:

**Civil Engineering & Construction Management**  
Provides understanding of project-based businesses, construction financing requirements, and infrastructure-related decision making.

**Banking & Finance**  
Provides a credit-oriented perspective for evaluating borrowers, financial characteristics, portfolio quality, and financing risk.

**Data Analytics**  
Provides the analytical framework for transforming financial data into measurable insights and interactive decision-support tools.

## Certification Context
This project was developed as part of my Data Analyst learning and professional competency journey.

Supporting credentials included in this repository:
- **BNSP Data Analyst Competency Certification**
- **DQLab Data Analyst Program**

The certifications are included as supporting evidence, while this repository focuses primarily on the underlying analytical work and project artifacts.

## Key Learning Outcomes
Through this project, I strengthened my ability to:

- Translate financial and business problems into analytical questions.
- Perform structured exploratory data analysis.
- Analyze credit and portfolio risk indicators.
- Prepare analytical datasets for business intelligence tools.
- Develop interactive Power BI dashboards.
- Connect domain expertise with data-driven decision making.
- Communicate analytical findings to business stakeholders.

## Future Improvements
Potential extensions of the project include:

- Predictive credit risk modeling.
- Probability-of-default estimation.
- Machine learning-based borrower risk classification.
- Portfolio stress testing.
- Construction-sector-specific financing datasets.
- Automated ETL pipelines.
- Deployment of an interactive analytics application.

---

**Author:** Farhan Prima Chandra  
**Focus:** Civil Engineering × Finance × Data Analytics
