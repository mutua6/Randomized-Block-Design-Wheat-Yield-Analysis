# Randomized-Block-Design-Wheat-Yield-Analysis
A statistical analysis of wheat yield using Randomized Block Design (RBD) in R. This project investigates the effects of geographical areas and yearly variations on crop output, featuring a complete R Markdown workflow, hypothesis testing, and ANOVA interpretation.
# Randomized Block Design Analysis of Wheat Yield

## 📊 Project Overview
This analysis utilizes a **Randomized Block Design (RBD) with Replication** to evaluate wheat yield data. The study focuses on three treatments (Geographical Areas) and three blocks (Years) to identify significant drivers of production.

## 🛠 Statistical Methodology
The analysis follows the linear model:
$$Y_{ijk} = \mu + \alpha_i + \beta_j + (\alpha\beta)_{ij} + \epsilon_{ijk}$$



## 🧪 Analysis Highlights
- **Language:** R
- **Tooling:** R Markdown, LaTeX
- **Test Type:** Two-Way Factorial ANOVA
- **Significance Level:** $\alpha = 0.05$

## 📂 Repository Contents
- `sps.Rmd`: Source code containing data entry and ANOVA computations.
- `Randomized-Block-Design-Wheat-Yield-Analysis`: The rendered technical report.

## 📈 Summary of Results
The model successfully identifies whether geographical area or yearly variation (blocks) significantly impacts yield, while specifically testing for the interaction effect between the two variables.
