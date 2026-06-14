# Leveraging Machine Learning Algorithms and Explainable AI for Predicting Mental Health Disorder Treatment at the Workplace

## Overview

This repository provides reproducible materials for a workplace mental health prediction study. The analysis evaluates machine learning algorithms and explainable artificial intelligence methods to predict whether individuals seek or receive treatment for mental health disorders in workplace-related survey data.

## Repository

- **Repository name:** `Mental-Health-Manuscript`
- **Repository type:** Jupyter Notebook research repository
- **Repository link:** https://github.com/Agyemang1z/Mental-Health-Manuscript
- **Authors:** Candanedo, Daniella, Agyemang Fosu Edmund, Chaudhry Farhana, Taylor Franks, Taylor Bailey, Siliezar Kevin, & Samuel Kakraba
- **Academic identifier:** ORCID: https://orcid.org/0000-0001-8124-4493

## Repository Contents

The public repository listing identifies the following files:

- `Mental Health Manuscript.ipynb`
- `Mental Health Survey Data.csv`
- `README.md`

## Research Objectives

- Predict mental health treatment status using workplace and individual-level predictors.
- Compare traditional and advanced machine learning classifiers.
- Use SHAP to identify features that contribute most strongly to model predictions.
- Support transparent reporting of predictive performance and model interpretation.

## Analytical Workflow

1. Load the mental health survey dataset.
2. Clean and encode categorical variables.
3. Train logistic regression, random forest, gradient boosting, categorical boosting, support vector machine, and neural network models.
4. Evaluate predictive performance using accuracy, precision, recall, F1 score, and AUC.
5. Use SHAP-based interpretation to identify influential predictors.
6. Summarize findings for workplace mental health decision support.

## Software Requirements

Recommended software and packages include:

- Python 3.10 or later
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- scikit-learn
- matplotlib
- shap
- catboost

Package versions should be recorded before manuscript submission. Where possible, add a `requirements.txt`, `environment.yml`, `renv.lock`, or `sessionInfo()` output to improve reproducibility.

## Reproducibility Guide

Run the project from a clean working directory. The following commands provide a suggested starting point:

```bash
git clone https://github.com/Agyemang1z/Mental-Health-Manuscript.git
cd Mental-Health-Manuscript
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install pandas numpy scikit-learn matplotlib shap catboost jupyter
jupyter notebook "Mental Health Manuscript.ipynb"
```

If file names include spaces, keep quotation marks around the file name when launching notebooks or scripts from the terminal.

## Expected Outputs

- Model performance tables
- SHAP feature importance outputs
- Predictor ranking summaries
- Manuscript-ready analytical results

## Data Availability and Responsible Use

The data and code are provided for scholarly, educational, and reproducibility purposes. Users should verify the original data source, data license, and any use restrictions before redistribution or secondary analysis. When the dataset contains human, health, financial, or election-related information, results should be interpreted responsibly and reported with appropriate methodological caution.

## Suggested Citation

Candanedo, Daniela, Edmund Agyemang, Farhana Chaudhry, Taylor Franks, Bailey Taylor, Kevin Siliezar, and Samuel Kakraba. *Leveraging machine learning algorithms and explainable AI for predicting mental health disorder treatment at the workplace.* Acta Psychologica 267 (2026): 107081. [Source code and data]. GitHub. https://github.com/Agyemang1z/Mental-Health-Manuscript

## Keywords

Mental health, Workplace health, Machine learning, Explainable AI, SHAP, Predictive analytics

## Disclaimer

This repository is intended to support reproducible research. The code and outputs should not be used as a substitute for professional clinical, financial, legal, electoral, or policy judgment.
