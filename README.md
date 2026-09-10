# Hypothesis Testing using T-Statistic and F-Statistic

## Overview
This project applies statistical hypothesis testing — specifically t-tests and F-tests — to evaluate significance and compare variances across two subgroups of same dataset , i.e , from 1901-1930 time period and 1995-2024 time period.

## Objective
- Test whether observed differences in two considered time domains T1(1901-1930) and T2(1995-2024) are statistically significant
- Apply t-statistic for comparing means and F-statistic for comparing variances


## Data
- **Source:** HADISST
- **Groups/samples compared:**  SST data divided into two time domains ;T1 : 1901-1930 , T2 : 1995-2024
- **Sample size:** 1870-2025 , Global coverage

## Tools & Methods
- **Language:** Python (Jupyter Notebook)
- **Key libraries:** scipy.stats, numpy, pandas
- **Tests applied:**
  - **T-test:** to compare sample means at a significance level of p = 0.05
  - **F-test:** to compare variances between samples

## Results
The t-test rejected the null hypothesis (p > 0.05), indicating no significant difference in mean SST between the two groups. Whereas for a single group , the t-test accepted the null hypothesis (p > 0.05) . For f-test , p < 0.05 indicating that the variances of the two samples are significantly different  

## Skills Demonstrated
- Statistical hypothesis testing
- Interpretation of p-values and significance levels


## Author
Aaroksh Chauhan — M.Sc. Atmospheric and Oceanic Sciences, IIT Bhubaneswar
