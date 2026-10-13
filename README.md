# Marketing A/B Testing Analysis

## Project Overview

This project evaluates the effectiveness of an advertising campaign by comparing conversion rates between two experimental groups: Ad and PSA.

Using Python and statistical hypothesis testing, the analysis investigates whether the observed difference in conversion rates is statistically significant and translates the findings into actionable business recommendations.

This project was completed as part of the **Elevvo Pathways Data Analysis Internship**.

## Business Problem

Marketing teams need to determine whether advertising campaigns generate better conversion performance than alternative approaches.

The key business question is:

**Does the Ad group achieve a statistically significant higher conversion rate than the PSA group?**

## Project Objectives

* Compare conversion rates between the Ad and PSA groups.
* Calculate absolute and relative conversion lift.
* Perform a two-proportion Z-test.
* Estimate a 95% confidence interval for the conversion rate difference.
* Translate statistical findings into actionable business recommendations.

## Tools & Technologies

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* Jupyter Notebook
* Statistical Hypothesis Testing
* A/B Testing

## Analysis Workflow

### 1. Data Inspection

Examined the dataset structure, columns, data types, and basic statistics to understand the available information.

### 2. Data Preparation

Prepared the data for analysis and checked its suitability for comparing the experimental groups.

### 3. Exploratory Data Analysis

Explored the distribution of the experimental groups and examined conversion outcomes.

<img width="620" height="566" alt="1" src="https://github.com/user-attachments/assets/73a67500-ae6b-430e-8fce-6d06a47ca21e" />


### 4. Conversion Rate Analysis

Calculated and compared conversion rates for the Ad and PSA groups.

### 5. Statistical Hypothesis Testing

Defined the null and alternative hypotheses and established a significance level of 0.05.

### 6. Two-Proportion Z-Test

Applied a two-proportion Z-test to determine whether the observed difference in conversion rates was statistically significant.

<img width="569" height="577" alt="2" src="https://github.com/user-attachments/assets/c1d9b08c-5680-4c03-b748-ea06ae88c968" />


### 7. Conversion Lift & Confidence Interval

Calculated the absolute conversion lift, relative conversion lift, and 95% confidence interval for the difference between conversion rates.

### 8. Business Impact Analysis

Interpreted the statistical results in a business context and identified the additional information required to assess campaign profitability.

### 9. Final Insights & Recommendations

Summarized the findings, visualized the results, and developed recommendations for evaluating and optimizing advertising performance.

## Key Results

| Metric                   |                             Result |
| ------------------------ | ---------------------------------: |
| Z-statistic              |                             7.3701 |
| Significance Level       |                               0.05 |
| Absolute Conversion Lift |           0.7692 percentage points |
| Relative Conversion Lift |                             43.09% |
| 95% Confidence Interval  | 0.5951 to 0.9434 percentage points |
| Statistical Decision     |         Reject the null hypothesis |

The test results provide strong statistical evidence of a difference in conversion rates between the Ad and PSA groups.

The Ad group achieved a higher conversion rate, with an estimated relative lift of 43.09%.

The 95% confidence interval for the absolute difference lies entirely above zero, supporting the conclusion that the difference is statistically significant at the 5% significance level.

## Visualizations

### Conversion Rate Comparison

Compares the observed conversion rates of the Ad and PSA groups.

<img width="337" height="535" alt="3" src="https://github.com/user-attachments/assets/785697c5-5731-496a-9560-fc8234696dea" />


### Conversion Lift & Confidence Interval

Visualizes the estimated conversion rate difference and its 95% confidence interval.

<img width="602" height="541" alt="4" src="https://github.com/user-attachments/assets/2d5a8820-af4f-4d2c-bc80-7497ab51a362" />


## Business Insights

* The Ad group achieved a higher conversion rate than the PSA group.
* The observed difference was statistically significant.
* The relative conversion lift was 43.09%, indicating a substantial improvement relative to the PSA baseline.
* Statistical significance alone does not establish campaign profitability.

## Recommendations

1. Evaluate advertising costs and cost per conversion before increasing campaign spending.
2. Compare conversion performance across relevant audience segments to identify optimization opportunities.
3. Assess revenue, customer acquisition costs, and profitability before scaling the campaign.
4. Continue monitoring conversion performance to validate the observed improvement.

## Limitations

This analysis evaluates conversion performance but does not independently establish the campaign's financial return.

A profitability assessment would require additional information, such as advertising expenditure, revenue per conversion, and other relevant acquisition costs.

The interpretation also depends on appropriate experimental assignment, valid observations, and the assumptions of the statistical test.

## Repository Contents

* `Elevvo_Task_10_AB_Testing.ipynb`: Notebook containing the analysis, statistical testing, visualizations, and recommendations.
* `screenshots/`: Images of the main analytical visualizations.
* `README.md`: Project documentation.
* `LICENSE`: MIT License for the project code, subject to any third-party rights.

## Acknowledgment

Completed as part of the Elevvo Pathways Data Analysis Internship.

The project demonstrates the application of Python, statistical analysis, and business reasoning to evaluate marketing campaign performance.
