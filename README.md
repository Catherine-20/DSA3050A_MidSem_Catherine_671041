# DSA3050A_MidSem_Catherine_671041
# DSA3050A Mid-Semester Practical Examination

## Student Information
- **Name:** Catherine Ingabire
- **Student ID:** (your ID here)
- **Instructor:** Prof. Austin Owur Odera
- **Semester:** Spring 2026

## Dataset Source
- **Name:** Credit Card Transactions Fraud Detection Dataset
- **URL:** https://www.kaggle.com/datasets/kartik2112/fraud-detection
- **Rows:** 100,000 (fraudTrain) + fraudTest appended
- **Columns:** 22 columns

## Business Problem
SecureBank Financial Services engaged a BI Analyst to analyze credit card transaction data to identify fraudulent patterns, monitor fraud trends over time, and support data-driven fraud prevention decisions.

## Power Query Transformations Performed
### Basic Cleaning
- Renamed 12 unclear columns
- Changed data types for key columns
- Removed duplicate records
- Removed blank rows
- Trimmed and cleaned text columns
- Replaced inconsistent gender values (M/F → Male/Female)
- Removed 5 unnecessary columns

### Intermediate Transformations
- Split Transaction_DateTime into Transaction_Date and Transaction_Time
- Merged first and last name into Full_Name
- Created custom Fraud_Risk_Score column
- Created conditional Transaction_Status column
- Extracted Year, Month, Quarter and Day from date column
- Filtered rows by two conditions
- Sorted data by Transaction_Amount descending
- Added Index column

### Advanced Tasks
- Appended fraudTest dataset to fraudTrain
- Performed Column Profiling on entire dataset
- Applied Group By with multiple aggregations
- Extracted text before delimiter from merchant column
- Created business Amount_Category using nested conditional logic

## Visuals Created
1. KPI Card — Total Transactions
2. KPI Card — Total Fraud Cases
3. KPI Card — Total Transaction Amount
4. Bar Chart — Fraud Cases by Category
5. Column Chart — Transaction Amount by Gender
6. Line Chart — Monthly Fraud Trend
7. Pie Chart — Fraud vs Legitimate Transactions
8. Table Visual — Transaction Details
9. Matrix Visual — Transaction Amount by Category and Gender
10. Map Visual — Transaction Amount by State
11. Donut Chart — Transaction Amount by Risk Category
12. Treemap — Transaction Amount by Category

## Business Insights
1. High fraud concentration in grocery, shopping and entertainment categories
2. High value transactions above $1,000 show higher fraud probability
3. Geographic clustering of fraud in specific states suggests organized fraud rings

## Dashboard Link
(paste your Power BI published link here)

## GitHub Repository
(paste your GitHub link here)
