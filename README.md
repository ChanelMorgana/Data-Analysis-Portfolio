# 📊 Data Analysis Portfolio
Chanel W.'s Data Analysis Portfolio

This repository showcases two end-to-end data analysis projects, one small project (500 rows) with 2 visualizations created solely in **Excel** and one much larger project (100k rows) cleaned and transformed in Excel and Visualized in **Tableau**.
---

## Project 1: Insurance Data Analysis (Excel)

**Description**:  
Analyzed a dataset of 500 insurance policies using Excel. Focused on data manipulation, cleaning, and visual reporting.

### Tools & Techniques
- Microsoft Excel
- `SUMIF`, `LOOKUP`, `MID`, `LEFT`, `RIGHT`, `LEN`, `FIND`, `TRIM` functions
- Pivot Tables
- Line & Bar Charts

### Key Highlights
- **Formula Logic**:
  - Calculated insured value by state using `SUMIF`.
  - Populated business types with lookup based on policy numbers.
- **Text Extraction**:
  - Parsed and cleaned raw policy descriptions using string formulas.
- **Data Visualization**:
  - Built pivot tables and charts:
    - **Line Chart**: *Expiry Date vs Insured Value*
    - **Bar Chart**: *Total Value by Code (Descending)*

---

## Project 2: Retail Transactions Analysis + Tableau Dashboard

**Dataset**:  
[Retail Transactions Dataset (Kaggle)](https://www.kaggle.com/datasets/prasad22/retail-transactions-dataset)

**Description**:  
Analyzed 100,000 rows of retail transactions, enriched the dataset for demographic and product-level insights, and visualized the findings in Tableau.

### Tools & Techniques
- Excel (for data prep)
- Tableau (for visualization)
- Data cleaning, reshaping, aggregation

### Key Highlights
- **Data Enrichment**:
  - Added `State` column for demographic breakdown.
  - Created a `Products` table by separating items per transaction.
  - Added Product Count per Product Type
- **Interactive Tableau Dashboard**:
  - **KPIs**: Total Transactions, Total Revenue
  - **Line Chart**: Revenue per Store Type
  - **Heatmap**: Sales by Location
  - **Pie Chart**: Discounts Distribution
  - **Bar Chart**: Consumer Profile
  - **Tables**:
    - Average Order Cost per Promotion
    - Product Purchases Summary

---



## 📁 Repository Structure
- Readme
- Insurance Data Analysis
- Retail Transactions Analysis
  - Tableau Dashboard
