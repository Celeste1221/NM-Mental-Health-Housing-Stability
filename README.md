# Mental Healthcare Access and Housing Stability in New Mexico

## Project Overview

This project investigates the relationship between mental healthcare access and housing stability across New Mexico counties. Using publicly available county-level data, the analysis explores whether access to mental health providers is associated with housing instability after accounting for socioeconomic factors.

The project combines statistical modeling and machine learning techniques to identify important predictors of housing burden and explore patterns among counties that may inform public policy and resource allocation.

## Project Contributors

This data science capstone was developed collaboratively by three team members. The project involved data collection, cleaning, exploratory data analysis, statistical modeling, machine learning, and interpretation of findings.

**Contributors:**
- [@Celeste1221](https://github.com/Celeste1221)
- [@eljaysmithdata](https://github.com/eljaysmithdata)
- [@raven-in-space](https://github.com/raven-in-space)

## Research Question

**What relationship, if any, exists between mental healthcare access and housing stability in New Mexico?**

This project was designed to support policymakers, public health agencies, and nonprofit organizations working in mental health, housing, and homelessness by providing a data-driven analysis of county-level trends.

## Data Sources

### County Health Rankings & Roadmaps — 2025 Release

Primary variables included:

- Mental Health Providers
- Poor Mental Health Days
- Severe Housing Cost Burden
- Children in Poverty
- Unemployment
- Income Inequality
- Child Care Cost Burden
- Median Household Income

### HUD Comprehensive Housing Affordability Strategy (CHAS)

CHAS data were explored for additional housing affordability measures but were not incorporated into the primary statistical models. Differences in time periods, dimensionality, and variable structure made direct integration with the County Health Rankings data problematic within the scope of this project.

Additional public data sources related to healthcare access and homelessness were also explored during the data-collection phase.

## Tools & Technologies

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn

## Methods

### Data Preparation

- Filtered data to New Mexico counties
- Selected county-level mental health, housing, and socioeconomic indicators
- Converted variables to appropriate numeric data types
- Verified data completeness and evaluated missing values
- Examined descriptive statistics and potential outliers

### Exploratory Data Analysis

- Summary statistics
- Correlation analysis
- Scatterplots and data visualization
- Multicollinearity assessment using Variance Inflation Factor (VIF)
- Outlier and influence diagnostics

### Ordinary Least Squares Regression

OLS regression was used as the primary inferential method to examine the association between mental healthcare access and severe housing cost burden while estimating effect sizes, statistical significance, and model fit.

### Random Forest Regression

Random Forest regression was used as a complementary machine learning approach to examine feature importance and capture potential nonlinear relationships among the selected variables.

### K-Means Clustering

K-Means clustering was used to group counties according to shared mental health, housing, and socioeconomic characteristics and identify distinct county profiles.

## Key Findings

- Mental Health Provider availability showed a meaningful association with Severe Housing Cost Burden in the modeling analysis.
- Child Care Cost Burden also emerged as an important predictor of housing burden.
- Poor Mental Health Days showed limited evidence of a direct linear relationship with Severe Housing Cost Burden.
- Random Forest feature importance provided complementary evidence about the importance of Mental Health Providers and Child Care Cost Burden.
- K-Means clustering identified four county profiles, with Los Alamos County forming a distinct socioeconomic cluster.

These results describe county-level associations and should not be interpreted as evidence that mental health provider availability directly causes changes in housing stability.

## Data Limitations

One of the most important findings of this project was the limitation of currently available public datasets.

County-level data allowed broad associations to be explored, but the available sources did not provide a single integrated dataset combining mental healthcare access, healthcare utilization, housing instability, homelessness, and social determinants of health.

Differences in reporting periods and geographic granularity also limited the ability to directly combine some datasets.

These limitations highlight the value of additional publicly available, privacy-preserving datasets that better support research at the intersection of healthcare and housing policy.

## Future Work

Potential extensions of this project include:

- Incorporating HUD Point-in-Time homelessness counts
- Integrating additional healthcare workforce data
- Examining behavioral health utilization through Medicaid or Medicare claims where appropriate data are available
- Expanding the analysis to multiple states
- Evaluating additional housing and healthcare indicators
- Applying cross-validation and additional model evaluation techniques
- Building an interactive dashboard for policymakers and nonprofit organizations

## Skills Demonstrated

- Data Cleaning and Preparation
- Exploratory Data Analysis (EDA)
- Statistical Modeling
- Ordinary Least Squares Regression
- Random Forest Regression
- K-Means Clustering
- Feature Importance Analysis
- Model Diagnostics
- Multicollinearity Assessment
- Data Visualization
- Public Health Analytics
- Policy-Focused Data Interpretation
