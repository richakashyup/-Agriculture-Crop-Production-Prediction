# Agriculture Productivity Analysis and Prediction

This project focuses on analyzing agricultural productivity and predicting crop production efficiency using machine learning techniques. It employs advanced exploratory data analysis (EDA) and a regression-based approach to understand and forecast agricultural performance.

---

## Features
- **Data Cleaning and Preparation**: Preprocessing agricultural datasets for robust analysis.
- **Exploratory Data Analysis (EDA)**: 
  - Central tendency, dispersion, and distribution analysis.
  - Visual insights using histograms, scatter plots, and pair plots.
- **Machine Learning**:
  - Implementation of a Random Forest Regression model to predict Crop Productivity Index (CPI).
  - Feature importance analysis to understand key predictors.

---

## Dataset Details
The dataset (`AgrcultureDataset.csv`) includes agricultural statistics such as:
- Crop production and area.
- Year-wise breakdown for trends.
- Efficiency measures calculated as the Crop Productivity Index (CPI).

The CPI is a derived feature representing crop production efficiency in terms of the area utilized.

---

## Methodology
1. **Feature Engineering**:
   - Creating new metrics like CPI to enhance predictive power.
2. **Exploratory Data Analysis**:
   - Identifying distributions, relationships, and trends in the dataset.
   - Visualizations include:
     - Pair plots to reveal relationships between variables.
     - Bar plots for feature importance visualization.
     - Residual analysis for model evaluation.
3. **Machine Learning Model**:
   - Random Forest Regression for CPI prediction.
   - Residual and feature importance analysis to evaluate and interpret model performance.

---

## Requirements
To run this project, install the dependencies:

```bash
pip install -r requirements.txt
