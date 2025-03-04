# Pymaceuticals Inc. - Tumor Treatment Analysis

## Background

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

## Overview

This Jupyter Notebook analyzes data from a pharmaceutical study on mice to evaluate the efficacy of different drug regimens in reducing tumor sizes. The study involves tracking tumor growth over time for mice treated with different drugs and analyzing trends in tumor size, weight correlation, and statistical significance.

## Key Findings

- There is a **positive correlation** between the weight of the mice and tumor size, with an **r-value of 0.84**.
- **Capomulin** and **Ramicane** are the most effective treatments for reducing tumor sizes.
- **Infubinol** and **Ceftamin** are the least effective treatments.

## Requirements

Ensure you have the following dependencies installed before running the notebook:

```bash
pip install pandas matplotlib scipy
```

## Data Sources

The study uses two CSV files:

- `Mouse_metadata.csv` – Contains metadata about the mice used in the study.
- `Study_results.csv` – Contains tumor measurements taken during the study.

## Notebook Contents

1. **Data Preprocessing**
   - Importing and merging datasets.
   - Handling duplicate data.
2. **Summary Statistics**
   - Calculating key statistics (mean, median, variance, etc.) for tumor size.
3. **Visualizations**
   - **Bar Chart**: Number of observed mouse timepoints for each drug regimen.
   - **Pie Chart**: Distribution of male vs. female mice in the study.
   - **Line Plots**: Tumor size over time for different treatments.
   - **Scatter Plots**: Correlation between tumor size and weight.
4. **Statistical Analysis**
   - Hypothesis testing using **t-tests** to compare drug efficacies.

## How to Use

1. Clone the repository (if applicable) or download the notebook.
2. Place the CSV files in the `data/` directory.
3. Open the notebook in Jupyter Notebook or Jupyter Lab.
4. Run all cells to execute the analysis.

## Contact

For any questions or suggestions, feel free to reach out!
