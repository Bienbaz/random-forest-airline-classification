# Random Forest – Airline Customer Satisfaction Analysis

## Dataset
- File: `Invistico_Airline.csv`
- Target: `satisfaction` (satisfied vs neutral/dissatisfied)

## Methodology
- Three-way split (60/20/20) to prevent data leakage
- GridSearchCV + PredefinedSplit for hyperparameter tuning
- Compared Random Forest vs Decision Tree

## Results
Random Forest achieves higher accuracy, F1-score, and better generalization.

## Business Insight
Improving Inflight entertainment, Online boarding, and Seat comfort will have the biggest impact on passenger satisfaction.

See `random_forest_airline.ipynb` for full analysis.
