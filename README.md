# Groundwater Quality Assessment using Stacking Ensemble Learning

This repository contains the source code for the paper:

> **"Groundwater Quality Evolution in Jiyuan Plain: An Approach Combining EWQI, PCA, and Stacking Ensemble Learning"**

All models are implemented in Jupyter Notebooks (`.ipynb`) using Python 3.9.13.

## 📁 Repository Structure

| File | Model |
|------|-------|
| `Stacking.ipynb` | **Stacking ensemble model** (Level-0: RF, XGBoost, SVR; Level-1: Linear Regression) |
| `Random Forest.ipynb` | Random Forest Regressor |
| `Xgboost.ipynb` | XGBoost Regressor |
| `Catboost.ipynb` | CatBoost Regressor |
| `GBDT.ipynb` | Gradient Boosting Decision Tree |
| `Adaboost.ipynb` | AdaBoost Regressor |
| `Artificial Network.ipynb` | Multi‑layer Perceptron (MLP) |
| `Decision Tree.ipynb` | Decision Tree Regressor |
| `SVR.ipynb` | Support Vector Regressor |

Each notebook includes:
- Data preprocessing (EWQI calculation, PCA)
- Hyperparameter tuning (grid search / random search with 5‑fold cross‑validation)
- Model evaluation (R², MAE, RMSE)

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/109301/groundwater-ml-codes-public.git
cd groundwater-ml-codes-public


