# Investigate a Dataset – FBI Gun Background Checks

## Context & Objective
This project was completed as part of the Udacity Data Analyst Nanodegree Program.  
I worked with the FBI NICS Gun Background Check dataset, combined with socio-demographic indicators from the U.S. Census Bureau (income, poverty, education, population, etc.).  

Objective: Normalize firearm background checks per capita and explore whether demographic and economic factors are related to gun demand.

## Steps Taken

### 1. Data Preparation & Cleaning
- Converted date fields into usable time formats.  
- Handled missing values and removed duplicates.  
- Cleaned the demographic dataset by dropping irrelevant fields.  
- Aligned datasets by year for consistency.  
- Selected relevant firearm categories and computed state-level totals.  

### 2. Data Transformation
- Normalized firearm checks by population (per capita).  
- Restructured datasets for comparative analysis.  
- Combined firearm checks with Census features into a single dataset.

### 3. Exploratory Analysis
Census variables were grouped into thematic categories for structured comparisons:  

- Economy & Income: household income, poverty, per capita income  
- Population & Age: children, minors, elderly share  
- Gender: population by gender  
- Race & Ethnicity: racial/ethnic distribution  
- Service & Immigration: veterans, foreign-born residents  
- Housing & Living: household size, housing units, stability  
- Culture & Education: education level, language spoken at home  
- Health & Insurance: disability, uninsured rates  
- Employment & Labor: labor force participation, employment  

## Key Findings
- Large differences in firearm background checks per capita across states.  
- No strong or consistent correlation with income, poverty, education, age, or ethnicity.  
- Standard demographic indicators alone do not fully explain firearm demand variations.

## Deliverables
- Jupyter Notebook containing the full workflow (cleaning, transformations, analysis, visualizations).  
- HTML version for easier viewing and sharing.  
