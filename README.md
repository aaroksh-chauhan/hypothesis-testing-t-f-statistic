# Hypothesis Testing using T-Statistic and F-Statistic

## Overview
This project applies statistical hypothesis testing — t-tests and F-tests — to 
evaluate significance and compare variances across two subgroups of the same 
dataset, i.e., from the 1901–1930 time period and 1995–2024 time period.

## Objective
- Test whether observed differences in the two considered time periods, 
  T1 (1901–1930) and T2 (1995–2024), are statistically significant
- Apply a t-statistic for comparing means and an F-statistic for comparing 
  variances
- Test whether the mean and variability of sea surface temperature (SST) in 
  the Nino 3.4 region differs significantly between the early and recent 
  30-year periods

## Data
- **Source:** HadISST
- **Groups/samples compared:** SST data divided into two time domains — 
  T1: 1901–1930, T2: 1995–2024
- **Sample size:** 1870–2025, Global coverage (Nino 3.4 region subset used 
  for the comparison)

## Tools & Methods
- **Language:** Python (Jupyter Notebook)
- **Key libraries:** scipy.stats, statsmodels, numpy, xarray
- **Tests applied:**
  * **T-test:** to compare sample means at a significance level of p = 0.05
  * **F-test:** to compare variances between samples

## Results
- **Two-sample T-test (T1 vs T2 means):** T-statistic = -0.022, p = 0.983 — 
  no statistically significant difference in mean SST between the two periods
- **F-test (T1 vs T2 variances):** F-statistic = 1.635, p < 0.001 — the 
  variance in SST was significantly higher in the recent period (1995–2024) 
  compared to the early period (1901–1930)
- This suggests that while the average SST hasn't shifted significantly 
  between the two periods, the year-to-year variability has increased 
  meaningfully over time

## Skills Demonstrated
- Statistical hypothesis testing (Z-test, T-test, F-test)
- Confidence interval estimation (Z and T distributions)
- Interpretation of p-values and significance levels
- Working with gridded climate data (NetCDF) and regional data extraction

## Author
Aaroksh Chauhan — M.Sc. Atmospheric and Oceanic Sciences, IIT Bhubaneswar
