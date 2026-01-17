# Auditing Student Risk Models

This project analyzes an early-warning machine learning model used to identify at-risk students, with a focus on **who the model misses rather than how accurate it is**.

## What This Project Does
- Trains a student risk classification model (~93% accuracy, ~91% recall)
- Stops model tuning and performs **error analysis**
- Analyzes **false negatives** (students who needed help but were not flagged)
- Compares model behavior across gender, internet access, and parental education
- Runs **what-if simulations** (study time, absences) to see what changes reduce risk

## Key Insight
High overall accuracy can hide important blind spots.  
Some student groups are more likely to be missed, which is not visible from aggregate metrics alone.

## Files
- `who_gets_missed.ipynb` – main analysis notebook  
- `report.html` – exploratory data analysis (open locally in a browser)

## Conclusion
This project focuses on understanding **model failures and fairness**, not just predicting grades.
