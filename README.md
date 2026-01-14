# HR Analytics Dashboard – MySQL & Power BI Project

## Project Overview
This project demonstrates an end-to-end HR analytics workflow using SQL and Power BI. Employee data is analyzed, cleaned, and transformed in MySQL, exported as structured CSV files, and visualized through an interactive Power BI dashboard.

The workflow is designed to keep all business logic and metric calculations in SQL, ensuring a clean and efficient reporting layer.

---

## Business Objective
HR teams require clear visibility into workforce composition, retention, and attrition trends.  
This project aims to:
- Analyze employee demographics and workforce distribution
- Evaluate employee tenure and termination patterns
- Identify department-level and location-based trends
- Support HR decision-making using data-driven insights

---

## Project Workflow

### 1. Data Analysis in MySQL
All analysis begins in MySQL using SQL scripts.

Key steps include:
- Data cleaning and standardization
- Handling missing values
- Date normalization
- Feature engineering (age groups, employment duration, termination flags)
- Employee distribution and trend analysis
- Generation of key HR metrics

---

### 2. Exporting Insights to CSV
- SQL query outputs are exported into multiple CSV files
- Each CSV represents a clean, analysis-ready dataset
- This minimizes transformation logic inside Power BI
- Ensures optimized and consistent dashboard performance

---

### 3. Power BI Dashboard Development
Power BI dashboards are built using the exported CSV files.

#### Key Metrics & KPIs
- Average length of employment
- Employee distribution by department
- Gender ratio
- Race and ethnicity distribution
- Work location (Headquarters vs Remote)
- Yearly employee count changes
- Termination analysis

#### Visualizations Included
- Gender distribution charts
- Age group analysis
- Race distribution bar charts
- Employee trend line (2000–2020)
- Geographic distribution by state
- Department-wise termination rates
- Gender distribution within departments
- Employee distribution by work type (HQ / Remote)

---

## Dashboard Navigation
- **Page 1**: Overall HR Overview  
- **Page 2**: Age, Gender, and Department-Level Insights  

---

## Dataset
- Source: Public HR employee dataset
- Format: CSV
- Data includes employee demographics, employment history, and termination details

---

## Key Insights
- Average employee tenure is approximately 8 years, indicating stable retention
- Majority of employees fall within the 35–54 age group
- Headquarters employs more staff compared to remote locations
- States such as Ohio and Pennsylvania have the highest employee counts
- Certain departments show higher termination rates, indicating areas for HR review
- Gender distribution varies significantly across departments
- Employee count shows consistent changes over the period 2000–2020

---

## Tools & Technologies
- MySQL – Data cleaning, transformation, and analysis
- SQL – Feature creation and metrics generation
- CSV – Exported analytical datasets
- Power BI – Interactive dashboards and visualization
- GitHub – Version control and documentation
