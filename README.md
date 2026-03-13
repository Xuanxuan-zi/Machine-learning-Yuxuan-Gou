# Machine-learning-Yuxuan-Gou

This repository contains the final project materials for my machine learning project on perceived stress.

## Project Title

**Perceived Stress as a Social and Psychological Outcome: The Role of Socioeconomic Status, Psychosocial Resources, and Adverse Life Experiences**

## Project Overview

This project examines which sociodemographic, psychosocial, and life-course factors matter most for perceived stress. The main outcome variable is `pss4_total`, a measure of perceived stress.

The project compares several modeling approaches, including:

- OLS regression
- LASSO regression
- Random Forest
- SHAP-based interpretation

The goal is to assess whether psychological distress, psychosocial resources, and adverse life experiences contribute more strongly to perceived stress than demographic background alone.

## Main Findings

Across models, a similar pattern appears:

- Anxiety symptoms and depressive symptoms are the strongest predictors of perceived stress.
- Psychosocial resources, especially self-efficacy and family support, are associated with lower stress.
- Major life events and adverse childhood experiences also remain important.
- Demographic background matters, but it appears less central than psychological distress, coping resources, and difficult life experiences.

## Repository Structure

### `Script-Yuxuan/`
This folder contains the main project scripts and rendered output.

Files include:
- `Feature engineering-Yuxuan Gou.Rmd`: feature engineering and data preparation work
- `Yuxuan Gou-Final project.Rmd`: main R Markdown file for the final project analysis
- `Yuxuan-Gou-Final-project.html`: rendered HTML output of the full final project, including the main analysis, tables, figures, and model results

### `RESULTS/`
This folder contains key result tables used in the analysis and presentation.

Files include:
- `descriptive_tables.xlsx`
- `measures_and_variable_definitions.xlsx`
- `ols_original_robust_and_diagnostics.xlsx`
- `shap_top10_three_line_table.xlsx`

These files summarize descriptive statistics, variable definitions, OLS diagnostics, and SHAP-based results.

### Root files
- `FinalPaper-Yuxuan Gou.pdf`: final written paper
- `Slides.pptx`: final presentation slides
- `README.md`: repository description

## Methods

The project uses several analytic approaches for different purposes:

- **OLS regression** as an interpretable baseline model
- **LASSO** for variable selection and a more parsimonious model
- **Random Forest** for flexible prediction
- **SHAP values** for interpreting variable importance in the Random Forest model

Model performance is evaluated using:
- RMSE
- R²
- MAE

## Data

The project uses data from the **2023 Psychology and Behavior Investigation of Chinese Residents (PBICR)**.

- Sample size: **30,054**
- Outcome: perceived stress (`pss4_total`)
- Predictor groups:
  1. Sociodemographic factors
  2. Health and behavior factors
  3. Psychosocial resources
  4. Adversity / life-course factors

## Author

**Yuxuan Gou**
