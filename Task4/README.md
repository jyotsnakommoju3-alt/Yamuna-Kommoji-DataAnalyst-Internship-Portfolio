# Task 4: Data Storytelling & Statistical Validation

## ApexPlanet Data Analytics Internship

### Project Overview
This task focuses on communicating business insights through data storytelling and validating business hypotheses using statistical methods.

The analysis uses the sales dataset developed during the previous internship tasks.

## Objectives
- Analyze sales data and identify meaningful business insights.
- Formulate testable business hypotheses.
- Apply appropriate statistical tests.
- Interpret p-values and confidence intervals.
- Present findings and business recommendations.

## Dataset Overview
The dataset contains 1,000 records and 14 columns, including customer information, order details, product categories, sales amounts, and monthly information.

## Hypothesis Testing

### Test 1: Electronics Purchase Proportion by Gender

**Null Hypothesis (H₀):** The proportion of Electronics purchases is the same for male and female customers.

**Alternative Hypothesis (H₁):** The proportion of Electronics purchases differs between male and female customers.

**Statistical Test:** Chi-Square Test of Independence

**Significance Level:** 0.05

**Reported p-value:** 0.046

**Interpretation:** The reported p-value is below 0.05, indicating statistically significant evidence of an association between gender and Electronics purchase proportion at the 5% significance level. The result is close to the threshold and should be interpreted cautiously.

### Test 2: Average Sales by Gender

**Null Hypothesis (H₀):** The average sales amount is equal for male and female customers.

**Alternative Hypothesis (H₁):** The average sales amount differs between male and female customers.

**Statistical Test:** Welch's Two-Sample t-Test

**Reported p-value:** 0.495

**Interpretation:** The p-value is greater than 0.05. Therefore, the analysis does not provide sufficient evidence of a statistically significant difference in average sales between the two groups.

These tests address different business questions and should not be interpreted as contradictory.

## Key Business Insights
- Electronics is an important product category in the sales analysis.
- Statistical testing helps distinguish observed patterns from evidence of meaningful differences.
- Business decisions should consider statistical results alongside customer behavior and other business factors.

## Business Recommendations
- Investigate customer preferences across product categories.
- Use additional customer and transaction data before developing targeted marketing strategies.
- Avoid making decisions based only on a borderline statistical result.
- Continue monitoring sales patterns over time.

## Limitations
- The findings depend on the quality and structure of the available dataset.
- Statistical association does not establish causation.
- Repeated Order IDs may affect assumptions about independent observations.
- Further validation with additional data is recommended.

## Tools Used
- Microsoft Excel
- SQL / SQLite
- Statistical hypothesis testing
- Data visualization and presentation tools

## Deliverables
- Final presentation PDF
- Hypothesis testing report
- Statistical calculations, where applicable
- README documentation

## Conclusion
This task demonstrates how statistical validation and data storytelling can support data-driven business decisions. The results should be interpreted carefully, considering the dataset, statistical assumptions, and business context.

**Internship:** ApexPlanet Software Pvt. Ltd.  
**Domain:** Data Analytics
