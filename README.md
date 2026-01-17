# Auditing Student Risk Models

This project audits an early-warning machine learning model used to identify at-risk students.

Instead of focusing only on accuracy, the project analyzes:
- False negative errors (students who were missed)
- Fairness across gender, internet access, and parental education
- Ethical blind spots in high-performing models

## Files
- `student_risk_audit.ipynb` – main analysis notebook
- `report.html` – exploratory data analysis (pandas profiling)
- The EDA report (`report.html`) can be downloaded and viewed locally in a browser.

## Key Insight
Even highly accurate models can systematically miss vulnerable student groups, which is not visible from aggregate metrics alone.

### About

-I built an early-warning student risk model using tabular behavioral data and achieved around 93% accuracy and 91% recall.

-Instead of optimizing further, I froze the model and focused on error analysis.

-I analyzed false negatives and computed group-wise false negative rates across sensitive attributes like gender, internet access, and parental education.

-Despite strong aggregate performance, the model systematically under-identified at-risk students from certain groups, particularly those without internet access.

-I then ran counterfactual what-if simulations on false negatives by modifying only intervenable features like study time and absences, to quantify which actions actually reduce predicted risk.

-The project is essentially an audit of model blind spots rather than a grade prediction task.


