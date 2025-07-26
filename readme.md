# Credit Risk Prediction with Explainable AI

**Author:** Vijaya Sivanjan Kommuri 
**Date:** July 2025

## Overview

This project uses machine learning and Explainable AI (XAI) to predict credit risk from tabular financial data.  
Key features:
- Data preprocessing and encoding
- Random Forest classifier for prediction
- SHAP-based explainability to reveal feature importance and model trust

## Technologies Used
- Python 3.x
- pandas
- scikit-learn
- matplotlib
- shap

## Project Steps

1. **Data Preparation:** Load and clean GermanCredit dataset.
2. **Modeling:** Train a Random Forest classifier to predict credit risk.
3. **Evaluation:** Assess performance via accuracy and confusion matrix.
4. **Interpretability:** Use SHAP to explain which features most influence the predictions.

## Results

- **Test Accuracy:** (insert your value, e.g. 0.76)
- The most important features identified by SHAP are loan `[amount]`, `[duration]`, `[age]` (customize with your findings).

## Why Explainability?

In credit scoring, it’s crucial for models to be transparent and trustworthy, both for regulators and customers. SHAP visualizations make it clear which factors drive risk assessments.

## How to Run

1. Clone this repository.
2. Install required packages:
    ```
    pip install -r requirements.txt
    ```
3. Open `credit-risk-xai-project.ipynb` in Jupyter Notebook and run all cells.

## Sample Visualizations

_(Insert screenshots or example SHAP summary plot if desired, or say “See notebook for visualizations.”)_

## Next Steps/Future Work

- Try alternative models (e.g., XGBoost)
- Experiment with LIME for local explanations
- Test on other datasets (e.g., medical, legal)

---
