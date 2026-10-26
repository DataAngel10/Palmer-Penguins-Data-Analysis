# 🐧 Palmer Penguins Data Analysis in R

## Project
EDA and statistical testing of the **Palmer Penguins dataset** using R to analyze the relationship between
body mass and flipper length.

## 🛠️ Tech Stack
- **Language:** R (Jupyter Notebook)
- **Libraries:** `tidyverse`, `palmerpenguins`, `rstatix`

## 🔍 Key Highlights
- **Data Cleaning & Validation:** Handled missing values with justification and verified data integrity (N = 333).
- **EDA & Visualizations:** Built custom distribution charts, boxplots with jitter for outlier analysis, and multi-variable scatter plots
  (`ggplot2`).
- **Statistical Rigor:** Checked for normality (Shapiro-Wilk) and applied **Spearman’s rank correlation** (overall, by sex, and by species)
 due to non-normal distributions.
- **Main Finding:** Uncovered a strong, positive correlation between body mass and flipper length across all groups (strongest in Gentoo,
-  (rho = 0.73).
