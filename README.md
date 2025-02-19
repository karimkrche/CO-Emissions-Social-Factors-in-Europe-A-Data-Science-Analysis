# CO-Emissions-Social-Factors-in-Europe-A-Data-Science-Analysis
## Introduction
This project analyzes the evolution of CO₂ emissions in Europe over the past 20 years and explores the relationship between these emissions and various social factors. The objective is to examine how income and education levels influence both perceptions of climate change and the actual amount of CO₂ emitted.

## Data Sources
The datasets used in this project come primarily from:
- **Eurostat**: CO₂ emissions by country and sector.
- **ADEME**: Survey on social perceptions of climate change in France.
- **Eurostat (socio-economic data)**: Population distribution by education level.

## Technologies and Libraries
This project is implemented in **Python**, utilizing the following libraries:
- **Pandas** for data processing.
- **Matplotlib & Seaborn** for visualization.
- **Scipy & Statsmodels** for statistical tests and regression analysis.

## Methodology
1. **Data Preparation**: Importing and cleaning datasets.
2. **Descriptive Analysis**: Exploring CO₂ emission trends in Europe and identifying the most polluting countries and sectors.
3. **Exploratory Data Analysis**:
   - **Chi² tests** to assess the association between environmental concerns and social variables (income, education, age).
   - **Regression analysis (OLS)** to measure the relationship between education level and CO₂ emissions.

## Key Findings
- **Germany and the UK are the largest CO₂ emitters in Europe.**
- **The industrial sector and households (heating, transport) are the primary contributors to CO₂ emissions.**
- **No significant correlation between income level and environmental concern.**
- **Significant correlation between education level and environmental awareness.**
- **Higher education levels appear to be associated with lower CO₂ emissions.**

## Limitations and Future Work
- The regression model explains only **27%** of CO₂ emission variance.
- Incorporating additional variables (e.g., public policies, individual behaviors) could improve predictions.
- A **multivariate logistic regression** could be a better approach to evaluate factors influencing climate change perception.
