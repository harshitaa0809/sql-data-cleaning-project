# sql-data-cleaning-project
# 🧹 SQL Data Cleaning Project: Layoffs Dataset

## 📖 Project Overview
Raw data often contains inconsistencies, duplicate records, missing values, and formatting issues that can impact analysis. In this project, I used MySQL to clean and transform a real-world layoffs dataset into a structured, reliable, and analysis-ready format.

## 🎯 Business Goal
Prepare the dataset for accurate reporting and exploratory data analysis by improving data quality and consistency.

## 🔍 Data Quality Issues Addressed
✔️ Duplicate Records  
✔️ Missing Values  
✔️ Inconsistent Text Formatting  
✔️ Incorrect Date Formats  
✔️ Blank Fields  
✔️ Unnecessary Columns

## ⚙️ Data Cleaning Workflow
### 1. Data Inspection
- Reviewed the dataset structure
- Identified quality issues and inconsistencies

### 2. Duplicate Removal
- Used `ROW_NUMBER()` and CTEs to identify duplicate records
- Removed redundant entries

### 3. Data Standardization
- Standardized company names
- Standardized industry categories
- Corrected country naming inconsistencies

### 4. Missing Value Treatment
- Converted blank values to NULL
- Populated missing industry values where possible using SQL joins

### 5. Date Formatting
- Converted text-based dates into MySQL DATE format

### 6. Final Data Preparation
- Removed unnecessary columns
- Generated a clean dataset ready for analysis

## 💡 SQL Skills Demonstrated
- Common Table Expressions (CTEs)
- Window Functions
- ROW_NUMBER()
- JOIN Operations
- UPDATE Statements
- DELETE Statements
- ALTER TABLE
- Data Cleaning Techniques

## 🛠️ Tools Used
- MySQL
- SQL

## 📂 Repository Contents
| File | Description |
|--------|-------------|
| Data_Cleaning Project.sql | Complete SQL cleaning workflow |
| layoffs.csv | Raw dataset used in the project |

## 🚀 Key Outcome
Successfully transformed raw layoff data into a clean, standardized, and analysis-ready dataset, establishing a strong foundation for further exploratory and business analysis.

---
### 👩‍💻 Author
**Harshita Rao**  
Electronics & Telecommunication Engineering | AI & ML Honours  
Aspiring Data Analyst
