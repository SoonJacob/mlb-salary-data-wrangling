# MLB Salary and Sabermetrics: Data Wrangling Analysis

A data wrangling coursework project studying the question:

> Does MLB's labour market reward the skills that produce runs, and did that change after the early-2000s sabermetric revolution?

## Project objective

Integrate historical baseball datasets and investigate the relationships between player performance, compensation and changes in how performance is valued over time.

## Workflow

- Profile data quality and structure across numerous baseball source tables
- Inspect keys, missingness, coverage and integration requirements
- Join and transform relevant player, salary and performance data
- Engineer analysis-ready variables and compare periods
- Explore associations between performance measures and salary
- Apply regression-based analyses to support interpretation

## Technical emphasis

The project emphasises **data wrangling and relational data integration** rather than treating modelling as the sole objective. It demonstrates how analytical conclusions depend on appropriate joins, data quality decisions and feature definitions.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn and Jupyter Notebook.

## Notebook

The original coursework notebook is intended to be placed at `notebooks/mlb_salary_data_wrangling.ipynb`, with saved code-cell outputs available where present.

## Data availability

The datasets referenced in the assignment are not distributed in this repository. Consequently, not all analysis cells can be rerun until the source data and the required directory structure are restored. See [DATA_AVAILABILITY.md](DATA_AVAILABILITY.md).

## Interpretation

This is a historical analysis project, not a causal demonstration that any specific statistic determines salary. Findings should be read in the context of the joined dataset, available variables and methodological limitations.
