# Economic Growth & Food Security Analysis: Sub-Saharan Africa

## Project Overview
This capstone project analyzes the correlation between GDP growth and food security outcomes across 50 Sub-Saharan African countries using World Bank development indicators (1960–2023).

**Prepared by:** Ndubuisi Favour Adaku  
**Date:** July 2026  
**Internship:** AnalystLab Africa, Batch B

---

## Research Question
To what extent does macroeconomic growth (GDP) translate into improvements in food security and agricultural productivity in Sub-Saharan Africa?

---

## Dataset
- **Source:** World Bank World Development Indicators (WDI)
- **Countries:** 50 Sub-Saharan African nations
- **Time Period:** 1960–2023
- **Records:** 15,225 data points
- **Indicators:** 7 core development metrics

### Key Indicators
1. GDP (current US$)
2. GDP per capita (current US$)
3. Agriculture, forestry, and fishing (% of GDP)
4. Food production index (2014-2016=100)
5. Prevalence of moderate or severe food insecurity (%)
6. Poverty headcount ratio at $1.90 a day (%)
7. Life expectancy at birth (years)

---

## Key Findings

### KPI Summary (2023)
- **Life Expectancy:** 64.80 years
- **Food Insecurity:** 58.32% of population
- **Agriculture % GDP:** 19.25% average
- **Total SSA GDP:** $47.02 billion

### Main Insights
1. **Strong positive correlation** between GDP growth and development outcomes
2. **Persistent food insecurity** despite 63 years of economic growth
3. **Varied agricultural dependence:** Niger (highest) vs. Djibouti (lowest)
4. **Accelerated growth** from 1990s onwards
5. **Economic growth is necessary but not sufficient** for food security

---

## Recommendations

### For Development Organizations (FAO, WFP)
- Prioritize smallholder agriculture investment in countries with >50% food insecurity
- Use GDP-to-food-security correlation to target interventions effectively
- Establish multi-country programs combining growth support with food security initiatives

### For National Governments
- Link macroeconomic growth targets to food security outcomes
- Invest in agricultural extension services and climate-resilient farming
- Use policy mechanisms to support smallholder farmers

### For Data Monitoring
- Establish regular tracking of GDP-to-food-security correlation
- Create data dashboards for policy decision-making
- Monitor progress toward SDG 2 (Zero Hunger) and SDG 1 (No Poverty)

---

## Deliverables

### 1. Power BI Dashboard
- **File:** `SSA_Economic_Food_Security_Analysis.pbix`
- **Features:** 
  - 4 KPI cards (Life Expectancy, Food Insecurity, Agriculture %, GDP)
  - GDP trend line (1960–2023)
  - Scatter plot (GDP vs. Development correlation)
  - Bar chart (Agricultural contribution by country)
  - Interactive slicers (Country, Year range)

### 2. Final Report
- **File:** `SSA_Capstone_Final_Report.pdf`
- **Contents:** 8 sections + appendix, 5000+ words
- **Sections:** Executive Summary, Objective, Dataset, Data Cleaning, Methodology, Findings, Insights, Recommendations, Conclusion

### 3. Data Files
- **File:** `SSA_Economic_Food_Security_Analysis.csv`
- **Format:** Long format (15,225 rows × 6 columns)
- **Cleaned and ready for analysis**

### 4. Dashboard Screenshots
- Included in repository for quick reference

---

## Methodology

### Data Cleaning
- Filtered to 50 SSA countries and 7 core indicators
- Removed missing values (NaN handling)
- Converted wide format → long format
- Data validation and outlier examination

### Analysis Approach
- **Descriptive statistics:** KPI calculation (2023)
- **Trend analysis:** 1960–2023 patterns
- **Correlation analysis:** Scatter plot visualization
- **Comparative analysis:** Country ranking by agriculture contribution
- **Interactive visualization:** Power BI dashboard

---

## Technologies Used
- **Data Processing:** Python, Pandas
- **Visualization:** Microsoft Power BI
- **Data Source:** World Bank WDI API
- **Version Control:** GitHub

---

## Key Takeaway
While Sub-Saharan Africa has achieved significant economic growth over six decades, this growth has not automatically translated to food security for the majority of the population. **Targeted investments in agriculture and food systems, paired with sustained economic growth, are essential for achieving food security and development goals.**

---

## Repository Contents
