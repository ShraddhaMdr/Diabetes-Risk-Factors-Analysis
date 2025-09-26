# The Impact of Lifestyle & Socio-Economic Factors on Diabetes Risk  
*A Predictive Analytics Case Study (BRFSS 2015)*

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Made with R](https://img.shields.io/badge/Made%20with-R-blue)](https://www.r-project.org/)

## 📖 Project Summary  
This repository presents a case study to **predict diabetes status** using **lifestyle**, **health**, and **socio-economic** indicators from the **BRFSS 2015** dataset. Three models (Logistic Regression, Random Forest, LDA) are compared on metrics like accuracy, precision, recall, F1, and ROC-AUC.

## Files & Structure

| Folder / File | Description |
|---------------|-------------|
| `docs/` | Reports and web assets |
| &nbsp; ├ `Case_Study_SM_Final.docx` | Final written report |
| &nbsp; └ `CaseStudyAssignment3.html` | HTML version of assignment |
| `outputs/` | Model outputs, tables, results |
| &nbsp; ├ `Table_B1_Descriptives_by_Diabetes.csv` | Descriptive stats by diabetes class |
| &nbsp; └ `Table_C1_Logistic_Regression_Coefficients_and_OR.csv` | Coefficients & odds ratios from logistic model |
| `README.md` | This file |
| `.gitignore` | Rules for what to ignore in the repo |
| `LICENSE` | MIT license (if you add it) |

## Reproduce the Analysis

1. Clone this repository  
   ```bash
   git clone https://github.com/ShraddhaMdr/Diabetes-Risk-Factors-Analysis.git
   cd Diabetes-Risk-Factors-Analysis
