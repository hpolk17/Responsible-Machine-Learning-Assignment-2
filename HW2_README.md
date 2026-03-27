# COMPAS Explainability (HW2)

## 1. Purpose of the Analysis

This project builds on the Lecture 02 COMPAS model and focuses on
explaining model behavior using SHAP, LIME, and counterfactual
explanations.

THe goal of the assignemnet is to understand what features are driving predictions, how
different explanation methods compare, and whether the model raises any
fairness or governance concerns.

## 2. Python Libraries Used

-   pandas\
-   numpy\
-   matplotlib\
-   scikit-learn\
-   shap\
-   lime\
-   dice-ml

## 3. How to Reproduce the Results

1.  Make sure Python 3 is installed\
2.  Install required libraries: pip install pandas numpy matplotlib
    scikit-learn shap lime dice-ml\
3.  Open the notebook: COMPAS_HW2.ipynb\
4.  Run all cells to generate: SHAP beeswarm and waterfall plots\ LIME explanations\ DiCE counterfactuals

## Notes

-   The dataset is pulled from the same ProPublica source used in
    lecture\
-   This implementation follows Lecture 02 
