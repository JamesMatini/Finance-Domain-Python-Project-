# Finance-Domain-Python-Project-
Python-based loan analytics project built in Jupyter Notebook to compute KPIs such as loan applications, funded amount, amount received, average interest rate, and DTI. Includes trend, regional, loan term, employment, purpose, and home-ownership analysis to reveal key lending insights.


# 📊 Loan Portfolio Analytics Dashboard

A comprehensive Power BI dashboard for analyzing lending performance, tracking key loan metrics, and identifying trends across geographic regions and customer segments.

## 📈 Project Overview

This loan analytics solution provides financial institutions with deep insights into their lending operations, enabling data-driven decisions for portfolio management, risk assessment, and strategic planning. The dashboard tracks application volumes, funding patterns, repayment trends, and borrower characteristics.

## 🎯 Key Performance Indicators (KPIs)

### Core Lending Metrics
- **Total Loan Applications**: Number of loan applications received during specified period
- **MTD Loan Applications**: Month-to-Date application tracking for real-time monitoring
- **Total Funded Amount**: Total capital disbursed as loans
- **MTD Total Funded Amount**: Current month funding performance


  <img width="994" height="559" alt="image" src="https://github.com/user-attachments/assets/43d03cb7-1814-4fa7-9a64-d34b5a952868" />

- **Total Amount Received**: Borrower repayments and cash flow assessment
- **MTD Total Amount Received**: Current month collection performance


<img width="1017" height="533" alt="image" src="https://github.com/user-attachments/assets/9358eca5-55ec-4c01-ba88-66a2a6c4cf55" />

- **Average Interest Rate**: Portfolio-wide lending cost insights
- **Average Debt-to-Income Ratio (DTI)**: Borrower financial health assessment

## 📊 Visualization & Analysis

### Trend Analysis
- **Monthly Trends by Issue Date**: Line/Area chart identifying seasonality and long-term lending patterns
- **Performance Tracking**: Monitor application, funding, and collection trends over time

### Geographic Analysis
- **Regional Analysis by State**: Bar chart highlighting high-activity regions and regional disparities
- **State-wise Performance**: Compare lending metrics across different geographic locations

### Loan Characteristics
- **Loan Term Analysis**: Donut chart showing distribution across various term lengths
- **Term Preference Insights**: Understand borrower preferences for short vs long-term loans

### Borrower Demographics
- **Employee Length Analysis**: Bar chart examining lending metrics by employment history
- **Employment Impact Assessment**: Correlation between job stability and loan applications
- **Home Ownership Analysis**: Tree/Heat map showing hierarchical impact on lending patterns
- **Property Ownership Influence**: How home ownership affects loan applications and disbursements

### Purpose Analysis
- **Loan Purpose Breakdown**: Bar chart visualizing primary reasons for borrowing
- **Funding Allocation Insights**: Understand what borrowers are financing most frequently

## 🔧 Technical Implementation

### Data Model Structure
- **Loan Applications Table**: Application dates, amounts, and status
- **Borrower Demographics**: Employment length, home ownership, DTI ratios
- **Geographic Data**: State-wise distribution and regional analysis
- **Time Intelligence**: MTD calculations and trend analysis

### Interactive Features
## Monthly Trends by Issue Date for Total Funded Amount

Dynamic Filtering: Cross-filter across all visualizations
MTD Tracking: Real-time month-to-date performance monitoring
Comparative Analysis: Compare metrics across different dimensions
Drill-through Capability: Detailed analysis from summary to granular data

loan-portfolio-analytics/
│
├── Dashboard/
│   ├── Loan_Analytics.pbix
│   └── Data_Model_Schema.md
│
├── Data/
│   ├── Raw_Loan_Data/
│   ├── Processed_Datasets/
│   └── Data_Dictionary.csv
│
├── Documentation/
│   ├── KPI_Definitions.md
│   ├── Business_Requirements.md
│   └── User_Guide.md
│
└── Assets/
    ├── Dashboard_Preview/
    └── Analysis_Samples/

# Transforming loan portfolio data into strategic insights for optimized lending operations and risk-managed growth.
