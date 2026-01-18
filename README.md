# Predictive Financial Risk Modeling

## Problem
Assessing firm-level financial risk is critical for credit decision-making
and portfolio risk management. Traditional rule-based approaches often
fail to capture complex, non-linear risk patterns.

## Approach
- Built supervised machine learning models to predict financial risk
- Implemented LightGBM and XGBoost for classification
- Engineered financial ratio and firm-level features
- Evaluated model performance using accuracy, ROC-AUC, and recall

## Key Insights
- Gradient-boosting models outperformed baseline approaches
- Identified key financial indicators contributing to default risk
- Demonstrated robustness across different validation splits

## Business Impact

This model can be used by financial institutions to:
- Flag high-risk firms earlier for credit review
- Reduce default exposure through probabilistic risk scoring
- Support portfolio-level stress testing and capital allocation

The ensemble approach prioritizes stability and generalization over single-model optimization, making it suitable for real-world deployment scenarios.

## Limitations & Future Work

- Model performance may vary under distribution shift
- No temporal validation due to dataset constraints
- SHAP-based interpretability and calibration curves are planned
- Future versions may include monotonic constraints and cost-sensitive optimization


## Tools Used
Python | Pandas | Scikit-learn | LightGBM | XGBoost

