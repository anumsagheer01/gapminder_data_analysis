## Regression Analysis of Gapminder Data

### Project Overview

This project explores global life expectancy trends over a 50-year period using Gapminder data. It examines how economic factors, like GDP, relate to life expectancy and uses regression models to identify patterns, relationships, and outliers in the data. The analysis involves visualization, statistical modeling, and hypothesis testing.

### Objectives

1. Visualize global life expectancy trends over time.
2. Examine the relationship between GDP and life expectancy.
3. Develop and evaluate linear regression models to predict life expectancy.
4. Test regression assumptions and evaluate model fit using statistical techniques.

### Data Source

- The dataset is sourced from the [Gapminder Project](https://gapminder.org) and is available via [Jenny Bryan's GitHub](https://github.com/jennybc/gapminder).

### Methodology

#### 1. Data Exploration and Visualization
- **Scatter Plot**: Life expectancy across time to identify trends.
- **Violin Plot**: Distribution of life expectancy by year to examine skewness and modality.

#### 2. Regression Modeling
- Fit a **linear regression model** with life expectancy as a dependent variable and year as an independent variable.
- Add interaction terms for continent and year to refine the model.

#### 3. Model Evaluation
- Analyze residuals to check assumptions of normality and independence.
- Compare simpler models to those with interaction terms using F-tests.

#### 4. Statistical Testing
- Evaluate the significance of model coefficients and test hypotheses about relationships between variables.

### Key Findings

- **Global Trends**: Life expectancy generally increases over time, but the trend varies by region.
- **Economic Relationships**: GDP is positively correlated with life expectancy, although the relationship is non-linear in some regions.
- **Model Insights**: Interaction models reveal differences in life expectancy trends across continents.

### Tools and Technologies

- **Python Libraries**: pandas, matplotlib, seaborn, scikit-learn, statsmodels
- **Data Source**: Gapminder dataset (TSV format)

