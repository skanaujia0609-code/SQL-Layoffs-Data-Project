# 📊 Layoffs Dataset - SQL Data Cleaning & EDA
This project focuses on analyzing global layoffs using **MySQL Workbench**.  
Both **Data Cleaning** and **Exploratory Data Analysis (EDA)** are performed entirely using SQL — no Python or BI tools used.

## 🧹 1. Data Cleaning (SQL)
The following tasks were performed:
1. Removed duplicates  
2. Standardized formatting  
   - TRIM company names  
   - Standardized industry names  
   - Fixed country names  
   - Converted date from string → DATE  
3. Filled missing industry values using self-joins  
4. Removed rows with both total_laid_off and percentage_laid_off missing  
5. Final cleaned table: `layoffs_staging2`

## 📊 2. Exploratory Data Analysis (SQL)
The EDA includes:

- Total layoffs per company  
- Layoffs per industry  
- Layoffs by country  
- Layoffs by year  
- Maximum % laid off  
- Funding vs layoffs insights  
- Time-series trends  
- Companies with 100% layoffs  
- Top 10 companies by layoffs  
- Monthly and quarterly analysis
- 
## 🛠 Tools Used
- **MySQL Workbench**
- Dataset in CSV format

## 📈 Key Insights
- Tech industry had the highest number of layoffs  
- 2023 showed the largest spike  
- Startups with high funding had higher percentage layoffs  
- The US had the highest number of layoffs globally 
