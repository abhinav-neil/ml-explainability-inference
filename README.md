# Explainability & Inference in ML

## A jupyer (iPython) notebook to model explainability and inference in ML models, using bank customer transactions dataset for classification.

1. Preprocessing & Exploratory Data analysis (EDA)
    - load and clean data
    - summary statistics
    - Plot target value counts and model class imbalance
2. Random Forest and Permutation Importance
    - fit random forest classifier to train set
    - permutation importance using eli5
3. Decision Tree and Partial Dependence Plots (PDP)
    - fit decison tree to test set
    - draw trees using graphviz
    - partial dependence plots using pdp
4. SHapley Additive exPlanations (SHAP)
    - Predict targets using RFC on test set
    - Extract and plot SHAP values using shap
