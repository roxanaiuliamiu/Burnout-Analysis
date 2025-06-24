# Burnout-Analysis
This dataset simulates employee-level data for burnout prediction and classification tasks.

📄 Columns
Name — Synthetic employee name (for realism, not for ML use).

Age — Age of the employee.

Gender — Male or Female.

JobRole — Job type (Engineer, HR, Manager, etc.).

Experience — Years of work experience.

WorkHoursPerWeek — Average number of working hours per week.

RemoteRatio — % of time spent working remotely (0–100).

SatisfactionLevel — Self-reported satisfaction (1.0 to 5.0).

StressLevel — Self-reported stress level (1 to 10).

Burnout — Target variable. 1 if signs of burnout exist (high stress + low satisfaction + long hours), otherwise 0.

The notebook has taken us through an exploratory analysis of employee burnout data. I created several visualizations covering data distributions and variable relationships. My model used a logistic regression approach to predict employee burnout, and the predictors performance was measured using accuracy and a confusion matrix.
