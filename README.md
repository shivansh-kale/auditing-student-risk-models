# Auditing Student Risk Models

This project audits an early-warning machine learning model used to identify at-risk students.

Instead of focusing only on accuracy, the project analyzes:
- False negative errors (students who were missed)
- Fairness across gender, internet access, and parental education
- Ethical blind spots in high-performing models

## Files
- `student_risk_audit.ipynb` – main analysis notebook
- `report.html` – exploratory data analysis (pandas profiling)

## Key Insight
Even highly accurate models can systematically miss vulnerable student groups, which is not visible from aggregate metrics alone.
