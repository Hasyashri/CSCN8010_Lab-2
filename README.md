# Practical Lab 2 - Multivariate Linear Regression, Non-Parametric Models and Cross-Validation

---

This lab focuses on multivariate regression modeling using the **Diabetes dataset** provided by Scikit-Learn. We explore different algorithms including **Polynomial Regression**, **Decision Trees**, and **k-Nearest Neighbors**, along with appropriate data splitting, evaluation metrics, and model comparison.

## Objectives

---

- Load and understand the diabetes dataset using `sklearn.datasets.load_diabetes()`.
- Frame the machine learning problem: predicting diabetes disease progression one year after baseline.
- Perform exploratory data analysis (EDA) including statistics, visualizations, and correlation matrices.
- Train and evaluate:
  - **Univariate Polynomial Regression** on BMI feature (degrees 0 to 5).
  - **Multivariate Polynomial Regression** (degrees 2 and 3).
  - **Decision Tree Regressors** with varying max depths.
  - **kNN Regressors** with different values of k.
- Evaluate model performance using **R²**, **MAE**, and **MAPE** on train, validation, and test sets.
- Draw conclusions based on validation/test results and model complexity.
- Practice clear documentation, markdown explanation, and code readability.

## Project Structure

---

- lab2multivariate.ipynb # Main Jupyter Notebook (code + markdown + plots)
- requirements.txt # Python dependencies (created using pip freeze)
- README.md # This documentation file
- .gitignore # Ignores unnecessary and system files

## Instructions

---

- Clone the repo
- Create a virtual environment python -m venv venv
- Install dependencies: pip install -r requirements.txt
- Run the notebook step-by-step

## References

---

I used chatgpt,copilot,course material, and https://www.geeksforgeeks.org/detect-and-remove-the-outliers-using-python/ for the coding.

Dataset link : https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html


