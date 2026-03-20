# ESG Risk Insights Dashboard (S&P 500)

## Overview
This project presents an ESG Risk Insights Dashboard developed in Power BI to analyse and benchmark environmental, social, and governance (ESG) risk across S&P 500 companies.

The dashboard is designed to translate ESG metrics into decision-relevant insights, enabling users to identify risk concentration, sector-level patterns, and company-specific risk profiles.

---

## Dashboard Preview

### ESG Risk Relationships

### Leaders & Laggards

### Company Risk Profile

---

## Objectives
- Analyse ESG risk distribution across companies and sectors  
- Compare company-level risk against sector benchmarks  
- Identify high-risk and low-risk performers  
- Explore relationships between ESG pillars and total risk  

---

## Key Features

### 🔹 ESG Risk Relationships
- Scatterplots showing relationships between:
  - Total ESG risk and Environmental risk  
  - Total ESG risk and Social risk  
  - Total ESG risk and Governance risk  
- Identification of clustering patterns and outliers

### 🔹 Leaders & Laggards Analysis
- Top 5 companies with lowest ESG risk  
- Top 5 companies with highest ESG risk  
- Companies with highest controversy scores

### 🔹 Company Risk Profiling
- Company-level ESG risk score, percentile, and controversy level  
- Benchmark comparison against sector averages  
- Breakdown across Environmental, Social, and Governance pillars  

### 🔹 Interactive Filtering
- Dynamic slicers by:
  - Company (symbol)
  - Sector
  - Country  

---

## Methodology

### Data Preparation
- Cleaned and standardised ESG dataset  
- Handled missing values and inconsistencies  
- Structured data for analysis across companies and sectors  

### Data Modelling
- Built relationships between company, sector, and ESG metrics  
- Developed calculated measures for:
  - ESG risk score  
  - Percentiles  
  - Sector benchmarks  

### Dashboard Design
- Designed for clarity and comparability  
- Structured layout to guide analytical flow:
  - Overview → Benchmarking → Deep dive → Relationships  

---

## Key Insights

- ESG risk varies significantly across sectors, with certain industries showing consistently higher exposure  
- Strong positive relationships exist between total ESG risk and individual pillar scores, particularly Social and Environmental factors  
- Governance risk appears more compressed, with lower dispersion compared to other pillars  
- Outliers highlight companies with disproportionately high risk relative to their sector  

---

## Data Source
This project uses a publicly available dataset from Kaggle:

- S&P 500 ESG Risk Ratings — https://www.kaggle.com/datasets/pritish509/s-and-p-500-esg-risk-ratings

The dataset is used for demonstration and analytical purposes only.

---

## How to Use

1. Download the `.pbix` file from this repository  
2. Open in Power BI Desktop  
3. Use slicers to explore:
   - Sector-level ESG risk patterns  
   - Company-specific risk profiles  
   - ESG pillar relationships  

---

## Project Context
This project reflects applied experience in ESG analytics and risk-focused data analysis, with emphasis on:

- translating ESG metrics into structured insights  
- working with imperfect real-world datasets  
- building analytical tools for exploratory and comparative analysis  

---

## Limitations & Future Improvements

- Incorporate time-series ESG data for trend analysis  
- Extend coverage beyond S&P 500  
- Integrate forward-looking climate risk scenarios (e.g. NGFS)  
- Enhance statistical modelling (e.g. risk normalisation, z-scores)  

---

## Author
Linh Vu  
MSc Environmental Intelligence (Distinction)  
Focus: Climate risk, ESG analytics, and data-driven sustainability insights
