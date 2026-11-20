# Nonparametric Statistical Analysis

## Overview

This project explores nonparametric statistical methods using R, applied to the `Prestige` dataset, which contains information on 102 occupations in Canada during the 1970s.

The analysis focuses on density estimation, statistical hypothesis testing and nonparametric regression, exploring relationships between occupational income, prestige and the percentage of women in different occupations.

## Objectives

- Estimate and compare probability density functions using different nonparametric approaches.
- Analyse the impact of bandwidth selection on kernel density estimation.
- Assess the normality of the income distribution.
- Compare the distribution of the percentage of women across occupational groups.
- Model the relationship between income and occupational prestige using nonparametric regression methods.

## Methodology

### 1. Density Estimation

- Histograms with different origins.
- Kernel density estimation.
- Bandwidth selection using:
  - Rule of thumb.
  - Plug-in method (Sheather-Jones).
  - Least-squares cross-validation.
- Comparison with a fitted normal distribution.

### 2. Statistical Hypothesis Testing

- Assessment of the normality of occupational income.
- Comparison of the distributions of the percentage of women across two groups defined by occupational prestige.
- Graphical and analytical evaluation of statistical hypotheses.

### 3. Nonparametric Regression

- Nadaraya-Watson estimator.
- Local linear regression.
- Analysis of boundary effects.
- LOESS smoothing and prediction at selected income quartiles.

## Dataset

The analysis uses the `Prestige` dataset, available through the `carData` R package.

The dataset contains information about 102 Canadian occupations, including variables such as:
- `income`: Average occupational income.
- `prestige`: Occupational prestige score.
- `women`: Percentage of women in each occupation.

## Tools and Technologies

- R
- R Markdown
- Kernel Density Estimation
- Bandwidth Selection
- Statistical Hypothesis Testing
- Nonparametric Regression
- Data Visualisation

**Main R packages:** `carData`, `sm`, `KernSmooth`.

## Repository Structure

```text
nonparametric-statistics-analysis/
│
├── README.md
├── Nonparametric_Statistics.Rmd
└── Nonparametric_Statistics.pdf
```

## How to Run

1. Install R and RStudio.
2. Install the required packages:

```r
install.packages(c("carData", "sm", "KernSmooth"))
```

3. Open `Nonparametric_Statistics.Rmd` in RStudio.
4. Knit the document to reproduce the analysis and generate the PDF report.

## Project Context

This project was originally developed as part of an academic assignment within the Master's Degree in Statistics and Operations Research.

It is included in my personal portfolio to showcase my experience with statistical inference, nonparametric methods, data analysis and statistical programming in R.