# COVID-19 Data Analysis using R

## Abstract

This project aims to analyze COVID-19 data using R, with a focus on understanding the impact of age and gender on the mortality rate of infected individuals. By performing statistical analysis on a dataset of approximately 1,000 COVID-19 cases, the project seeks to verify common claims related to COVID-19 and identify vulnerable population groups.

## Problem Statement

1. The media claims that older people are more likely to die from COVID-19 than younger people. Is this true?
2. The media claims that men are more likely to die from COVID-19 than women. Is this true?

## Need and Importance

Analyzing a large dataset allows us to employ hypothesis testing methods to identify which groups of the population are more vulnerable to COVID-19 and have higher mortality rates when exposed to the virus. This information can be crucial in allocating resources and implementing targeted measures to protect these vulnerable groups, ultimately reducing the overall number of infections and deaths.

## Experiment and Analysis

The project follows the following general layout:

1. Defining the problem: Outlining the questions to address through data analytics and the desired solutions.
2. Collecting data: Importing and preparing the dataset for analysis.
3. Cleaning data: Ensuring data consistency by removing unnecessary and duplicate information.
4. Analyzing the data: Identifying trends and patterns in the dataset to understand the behavior of data.
5. Hypothesis testing: Using the t-test command to gauge the confidence and verify the claims.

## Findings and Results

### Age Analysis:

The data analysis indicates that people who died from COVID-19 are older on average compared to those who survived. A t-test with a 95% confidence interval confirms that the age difference between patients who died and those who survived is statistically significant. This suggests that older individuals are more likely to die from COVID-19.

### Gender Analysis:

The analysis reveals that men have a higher death rate (8.5%) compared to women (3.7%). The t-test with a 95% confidence interval indicates that this difference is statistically significant, supporting the claim that men are more likely to die from COVID-19.

## Conclusion

R facilitates statistical analysis on important datasets like COVID-19, enabling us to gain valuable insights and verify common claims. Understanding the impact of age and gender on COVID-19 mortality helps inform targeted interventions to protect vulnerable groups. Thank you for reading!

## References

- [COVID-19 Dataset](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset/version/25?select=COVID19_line_list_data.csv)

## Appendix

- Code File: [MAT2001_Project.R](link-to-code-file) (Replace `link-to-code-file` with the actual link to the code file)
