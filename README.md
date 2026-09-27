# Gender-Employment-Agricultural-Productivity
Regression analysis of gender-specific agricultural employment and agricultural value added across countries using Ordinary Least Squares (OLS).
# Gender-Specific Employment in Agriculture and Agricultural Productivity

## Research Paper

**Topic:** How does gender-specific employment in agriculture influence agricultural productivity and its contribution to GDP across diverse countries?

## Overview

This research project examines the relationship between gender-specific employment in agriculture and agricultural value added as a percentage of GDP across countries.

The study investigates whether the participation of male and female workers in agriculture is associated with agricultural productivity and the sector's contribution to overall economic output.

## Research Objective

The objective of the study is to examine the relationship between:

- Male employment in agriculture
- Female employment in agriculture
- Agricultural value added (% of GDP)

The study also examines the statistical significance of the estimated relationships using regression analysis.

## Data

The dataset contains observations for 167 countries.

### Dependent Variable

**Agriculture, value added (% of GDP)**

This measures the value added by agriculture, forestry, and fisheries as a percentage of a country's GDP.

### Explanatory Variables

**Employment in agriculture, male (% of male employment)**

The percentage of employed male workers engaged in agriculture.

**Employment in agriculture, female (% of female employment)**

The percentage of employed female workers engaged in agriculture.

**Data Source:** World Bank

## Methodology

The study uses a multiple linear regression model estimated using the Ordinary Least Squares (OLS) method under the Classical Linear Regression Model (CLRM) framework.

The estimated model is:

GDP_agri = β₀ + β₁ emp_m + β₂ emp_f + ε

where:

- GDP_agri = Agriculture, value added (% of GDP)
- emp_m = Employment in agriculture, male (% of male employment)
- emp_f = Employment in agriculture, female (% of female employment)
- β₀ = Intercept
- β₁ and β₂ = Regression coefficients
- ε = Error term

## Key Results

The estimated regression equation is:

GDP_agri = 1.233 + 0.297 emp_m + 0.109 emp_f

The model reports an R² of approximately **0.580**, indicating that around 58% of the variation in agricultural value added in the sample is explained by the two employment variables.

The coefficient on male agricultural employment is approximately **0.297** and is statistically significant at the 5% level.

The coefficient on female agricultural employment is approximately **0.109**. Its p-value is approximately **0.071**, so it is not statistically significant at the 5% level.

The overall regression is statistically significant based on the reported F-test.

## Statistical Analysis

The research includes:

- Descriptive statistics
- Scatter plots
- Multiple linear regression
- Interpretation of regression coefficients
- Individual significance tests for slope coefficients
- Joint significance testing
- F-test for overall goodness of fit
- R² interpretation

## Conclusion

The analysis finds a statistically significant relationship between male employment in agriculture and agricultural value added in the estimated model. The estimated coefficient for female agricultural employment is positive but does not reach statistical significance at the 5% level.

The paper also discusses the broader literature on gender participation in agriculture, access to resources, education, technology and agricultural productivity.

