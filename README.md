# Customer Churn Analysis — Telecom Industry

## Overview
End-to-end Python analysis of 7,000 telecom customers to identify churn drivers, segment high-risk customers, and deliver actionable retention recommendations. Combines statistical testing with machine learning feature importance.

## Business Problem
A telecom company is losing customers. The retention team needs to know: who is most at risk, why they leave, and what can be done about it.

## Tech Stack
| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data manipulation and analysis |
| Matplotlib, Seaborn | Data visualization |
| SciPy | Statistical hypothesis testing (independent t-test) |
| Scikit-learn | Random Forest feature importance |
| Jupyter Notebook | Interactive analysis environment |

## Analyses Performed
1. Overall churn rate and charge distribution
2. Churn by contract type — Month-to-Month vs. One Year vs. Two Year
3. Churn by customer tenure — lifecycle risk curve
4. Monthly charges analysis with statistical t-test (p-value reported)
5. Churn risk heatmap — contract type × internet service combination
6. Random Forest feature importance — top churn predictors ranked

## Key Findings
- Month-to-month customers churn at 3–4x the rate of two-year contract holders
- New customers (first 6 months) represent the highest churn risk window
- Churned customers pay significantly higher monthly charges (p < 0.05)
- Month-to-Month + Fiber Optic is the highest-risk customer segment
- Customers without online security or tech support churn at elevated rates

## How to Run
1. Open `churn_analysis.ipynb` in Jupyter Notebook or JupyterLab
2. Run all cells: Kernel → Restart & Run All
3. Charts render inline and are saved as .png files

## Output Charts
- `churn_overview.png` — Churn rate donut and charge box plot
- `churn_by_contract.png` — Churn rate and volume by contract type
- `churn_by_tenure.png` — Risk curve over customer lifecycle
- `churn_charges.png` — Charge distribution and internet service churn
- `churn_heatmap.png` — Contract × Internet risk grid
- `feature_importance.png` — Top predictors ranked by Random Forest

---
*Author: Shantanu Deshmukh | MS Computer Science, NJIT*
