# Assignment 4: Cohort Analysis

This project examines the relationship between smoking status, gender, and outcomes including cardiac events and healthcare expenditure using a simulated cohort dataset. Logistic regression is used to predict the probability of cardiac events, and linear regression models medical costs. The analysis includes interaction effects and presents results in both summary tables and visualization figures.

## Project Files

- `Assignment4.qmd` – Main Quarto file containing code, narrative, and formatted output
- `Data` – Contains the simulated dataset cohort.csv used for analysis
- `Assignment4.html` – Rendered HTML output of the report
- `references.bib` – Bibliography file for citations (if applicable)
- `images` - attached picture files

## Packages Installation

To run this project, you'll need R (≥ 4.0.0) and RStudio. All required packages can be installed using:

```r
install.packages(c(
  "tidyverse",
  "dplyr",
  "gtsummary",
  "gt",
  "ggeffects",
  "ggplot2",
  "modelsummary"
))
