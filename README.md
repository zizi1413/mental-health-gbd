🧠 Global Mental Health Burden (GBD 1990–2019)
**Python data preparation & exploratory analysis + Tableau dashboard**

This project examines the global burden of mental health disorders using data from the Global Burden of Disease (GBD) Study covering the years 1990–2019.  
The focus of the project is to prepare reliable, analysis-ready datasets in Python and to communicate insights through an analytical dashboard built in Tableau.
---
## Project workflow

The project was carried out in two clearly separated stages, reflecting a real-world analytics workflow.
### 1. Python: Data cleaning & exploratory analysis
Python was used to prepare and validate the raw GBD datasets before visualization.  
The following steps were performed:

- Cleaned and standardized multiple GBD mental health datasets (prevalence, DALYs rate, primary data coverage)
- Harmonized column names and formats across files
- Performed exploratory data analysis (EDA) to understand:
  - global trends over time (1990–2019)
  - country-level differences in mental disorder prevalence
  - relationships between disorders using correlation analysis
- Conducted preliminary clustering analysis to explore country-level mental health profiles
- Exported three clean, Tableau-ready CSV files

These steps ensured that the data used in the dashboard was consistent, interpretable, and free of structural issues.
---
### 2. Tableau: Dashboard & visual storytelling
All final visualizations and insights were developed directly in Tableau using the cleaned outputs from Python.

The Tableau dashboard explores:
- Global and regional trends in mental health burden over time
- Country-level comparisons across multiple disorders
- Distinct mental health burden profiles across countries
- Data availability and gaps in primary mental health reporting

> The Tableau dashboard itself is not publicly shared; screenshots are included in this repository for illustration.
---
## Key analytical questions
This project was designed to answer questions such as:
- How has the global burden of mental health disorders changed over the past three decades?
- Do anxiety and depression consistently co-occur across countries?
- Are there countries or regions with distinct mental health burden profiles?
- Where are the major gaps in primary data reporting for mental health disorders?

---
## Key insights (from the Tableau dashboard)
- Anxiety and depression often show similar global patterns, but the strength of their relationship varies across countries.
- Some countries exhibit unique burden profiles, with elevated levels of specific disorders rather than uniformly high prevalence.
- Regional trends reveal long-term increases in depression burden in several parts of the world.
- Primary data coverage for certain mental health disorders remains limited in many countries, highlighting monitoring and infrastructure gaps.

---
## Repository contents
- `notebooks/` — Python notebook for data cleaning and exploratory analysis  
- `data/processed/` — Cleaned CSV files used as inputs for Tableau  
- `dashboard/screenshots/` — Screenshots of the Tableau dashboard

---
## Tech stack
Python (pandas, numpy, matplotlib, seaborn, scikit-learn)  
Tableau  
Global Burden of Disease (GBD) Study data

---
## Author

Created by: zohreh samieekadkani
LinkedIn: https://www.linkedin.com/in/zohreh-samieekadkani-24204z1413/
