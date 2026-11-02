# 🌲 Machine Learning Zoomcamp - Homework 6: Decision Trees & Ensemble Learning

Welcome to my submission for **Homework 6** of the [DataTalksClub Machine Learning Zoomcamp](https://github.com/DataTalksClub/machine-learning-zoomcamp)! 🚀

This module focuses on tree-based algorithms, evaluation metrics, hyperparameter tuning, and gradient boosting using XGBoost.

---

## 📌 Topics & Concepts Covered

* **Decision Trees & Random Forests:**
  * Training and tuning `DecisionTreeRegressor` & `RandomForestRegressor`.
  * Evaluating model performance using **RMSE** (Root Mean Squared Error).
  * Feature Importance analysis to understand model decisions.

* **XGBoost & Gradient Boosting:**
  * Converting data into XGBoost's specialized `DMatrix` structure while maintaining feature names (`xgb.DMatrix`).
  * Training gradient-boosted trees over **100 boosting rounds** (`num_boost_round=100`).
  * Monitoring training vs. validation RMSE curves to observe model convergence.
  * Hyperparameter tuning (e.g., `eta` / learning rate, `max_depth`).

---

## 🛠️ Tech Stack & Libraries Used

* **Python 3.x**
* **Pandas & NumPy** (Data Manipulation & Preprocessing)
* **Scikit-Learn** (Decision Trees, Random Forest, Metrics)
* **XGBoost** (Gradient Boosting & DMatrix Evaluation)

---

## 📁 Repository Structure

```text
.
├── Hw6.ipynb        # Main Jupyter Notebook containing code, experiments, and answers
└── README.md        # Homework summary and documentation
