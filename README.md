# HR Data — Employee Analytics

Machine-learning notebooks on the HR employee dataset (`HR_comma_sep.csv`, 14,999 employees).

| Notebook | Question | Approach |
|---|---|---|
| [find_left_employee.ipynb](find_left_employee.ipynb) | Why do employees leave, and can we predict who will leave? | EDA, outliers, encoding, scaling, Logistic Regression, accuracy / precision / recall / confusion matrix |
| [promoted_employ.ipynb](promoted_employ.ipynb) | Which employees are likely to be promoted? | EDA by department, Logistic Regression with class weights |
| [k-means.ipynb](k-means.ipynb) | Which groups of similar employees exist? | Scaling, K-Means clustering, elbow method, silhouette score |

## Dataset columns

`satisfaction_level`, `last_evaluation`, `number_project`, `average_montly_hours`, `time_spend_company`,
`Work_accident`, `left`, `promotion_last_5years`, `Department`, `salary`

## Run

Python 3 with `pandas`, `numpy`, `matplotlib`, `seaborn` and `scikit-learn`. Open the notebooks from this folder so `./HR_comma_sep.csv` is found.
