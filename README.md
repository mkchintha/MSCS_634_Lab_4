## Course Details

**Course**: 2025 Summer - Advanced Big Data and Data Mining (MSCS-634-M40)  
**Lab**: Lab 4 - Regression Analysis with Regularization Techniques  
**Student**: Murali Krishna Chintha

---

## Purpose of the Lab

The purpose of this lab is to explore and compare multiple regression techniques using the Diabetes dataset from `sklearn.datasets`. The primary objectives of this lab include:

* Implementing simple linear regression, multiple linear regression, and polynomial regression.
* Applying Ridge and Lasso regression to understand the role of regularization in model performance.
* Evaluating each model using performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²).
* Visualizing regression results to analyze model behavior and interpret performance.

---

## Key Insights Gained

* Simple linear regression using the 'bmi' feature alone resulted in moderate predictive power and interpretability.
* Visualization techniques were essential for understanding model fit and diagnosing issues like underfitting and overfitting.
* Polynomial regression performance highlighted the trade-off between bias and variance.
* Ridge regression helped mitigate the impact of correlated features by shrinking coefficients.
* Lasso regression emphasized model simplicity by eliminating less impactful features.
* The choice of alpha in regularization had a direct influence on model complexity and generalization.
* Evaluation using multiple metrics (MAE, MSE, RMSE, R²) provided a comprehensive view of each model’s strengths and weaknesses.
* Model comparisons demonstrated the importance of aligning model selection with the specific characteristics and requirements of the dataset.
* Multiple linear regression provided better accuracy by leveraging all available features but is sensitive to multicollinearity.
* Polynomial regression with degree 2 demonstrated improved fit, whereas degree 3 began to show signs of overfitting.
* Ridge regression effectively reduced the impact of multicollinearity and improved generalization.
* Lasso regression not only regularized the model but also performed feature selection by shrinking some coefficients to zero.
* Regularization techniques proved essential for improving generalization and mitigating overfitting.

---

## Challenges Faced and Decisions Made

* The 'bmi' feature was selected for simple linear regression due to its known association with diabetes progression.
* Polynomial regression was implemented using degrees 2 and 3 to illustrate the impact of increasing model complexity.
* A range of alpha values was explored for Ridge and Lasso regression to examine their influence on model performance.
* Visualization techniques such as scatter plots and line plots were used extensively to interpret results.
* Consistent evaluation metrics were applied across all models to enable fair comparison.

---

## Repository Contents

* `Lab4_Regression_Analysis.ipynb`: Jupyter Notebook containing complete implementation, visualizations, and evaluation of all regression models.
* `README.md`: Summary of the lab purpose, key findings, and decisions made during analysis.

---

## Conclusion

This lab provided practical experience with several regression techniques and highlighted the significance of model evaluation and regularization. By working with the Diabetes dataset, we observed how model complexity and regularization influence performance, overfitting, and generalization. Ridge and Lasso regression in particular offered valuable insights into handling multicollinearity and enhancing model robustness.

This assignment underscores the importance of selecting the appropriate regression strategy based on dataset characteristics and project goals.
