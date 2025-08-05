# 📊 Gender-Based Income Disparity Analysis using NLSY97

## 🧪 Research Objective
**Is there a measurable income disparity between men and women?**  
Does this disparity shift when factoring in other influences like education, marital status, criminal background, drug use, early-life environment, and occupation?

To answer these questions, this project analyzes a curated subset of the **National Longitudinal Survey of Youth 1997 (NLSY97)** dataset. The dataset includes responses from thousands of individuals surveyed biennially since 1997.

---

## 📁 Project Files

- `Data_Analysis.Rmd` – Complete R Markdown script with preprocessing, analysis, and modeling  
- `Data_Analysis.html` – Rendered HTML report 
- `nlsy97.csv` – Cleaned and prepared dataset  

---

## 🛠️ Workflow Summary

This project follows a structured approach to data-driven investigation, covering:

### 📥 Data Preparation
- Variable renaming for clarity  
- Filtering invalid/missing data  
- Handling **topcoded income** values (top 2% replaced with average to preserve privacy)

### 📊 Exploratory Analysis
- Summary statistics: means, medians, and frequencies  
- Visualization by gender and additional variables (e.g., education, marital status, criminal history)  
- Use of boxplots, histograms, and bar charts to illustrate patterns  

### 🧪 Hypothesis Testing
- Conducted two-sample tests to evaluate income gaps  
- Built confidence intervals  
- Checked assumptions (e.g., normality) before applying tests  

### 📈 Regression Modeling
- Developed a **multiple linear regression model** with income as the response variable  
- Used gender and 6–12 other variables as predictors  
- Interpreted coefficients and validated model assumptions  

### 📝 Interpretation & Insights
- Presented evidence-backed conclusions  
- Discussed limitations, especially due to **income topcoding** and potential confounding factors  
- Considered broader implications of income inequality  

---

## 📌 Key Observations

- **A persistent income gap exists** between men and women  
- Variables such as **education level** and **criminal history** significantly influence income  
- Even after adjusting for multiple factors, **gender remains a strong predictor** of income  

---

## 🧰 Tools & Technologies

- **R / RStudio**  
- Core libraries: `ggplot2`, `dplyr`, `readr`, `broom`, `base R`  
- **R Markdown** for reproducible documentation  

---

## 📚 Data Source

**National Longitudinal Survey of Youth 1997 (NLSY97)**  
U.S. Bureau of Labor Statistics – [https://www.bls.gov/nls/nlsy97.htm](https://www.bls.gov/nls/nlsy97.htm)

---
