# Applied Analytical Modelling Projects

This folder contains advanced machine learning and analytical modelling projects developed as part of my academic coursework. All projects utilize the **Gold Futures** dataset for financial market analysis.

> **Disclaimer:** These notebooks are provided for portfolio demonstration only. Please do not copy or distribute without permission.

## Projects Overview

### 1. Feature Engineering
**File:** `Feature_engineer_Final.ipynb`

Demonstrates feature engineering techniques for financial time series prediction:
- Technical indicators: RSI (Relative Strength Index), MACD (Moving Average Convergence Divergence)
- Date decomposition (Year, Month, Day features)
- StandardScaler normalization
- Random Forest classification for price movement prediction
- Comparison of basic vs. advanced feature sets

### 2. Explainable AI (XAI)
**File:** `XAI_Final.ipynb`

Implementation of model interpretability techniques:
- **SHAP (SHapley Additive exPlanations):** TreeExplainer for Random Forest, Explainer for Logistic Regression
- **LIME (Local Interpretable Model-agnostic Explanations):** Local explanations for individual predictions
- Comparison of Random Forest and Logistic Regression interpretability
- Feature importance visualization

### 3. Time Series Forecasting
**File:** `Time_Series_Final.ipynb`

Gold price forecasting using modern time series methods:
- **Facebook Prophet:** Seasonality analysis, trend decomposition
- **AutoTS:** Automated time series model selection
- Evaluation metrics: R², MAE, MSE, RMSE
- 180-day forward price predictions

### 4. Fuzzy Logic & Clustering
**File:** `Fuzzy_Logic_Final.ipynb`

Fuzzy set theory applications in financial data:
- Triangular and Gaussian membership functions
- Fuzzy C-Means (FCM) clustering algorithm
- Silhouette score optimization for cluster selection
- Fuzziness parameter tuning (m = 1.5, 2.0, 2.5)

### 5. Generative Adversarial Networks (GANs)
**File:** `GAN-final.ipynb`

Synthetic financial data generation:
- Custom Generator and Discriminator architectures using TensorFlow/Keras
- MinMaxScaler preprocessing
- Hyperparameter tuning (epochs, batch size, learning rate)
- Comparison of real vs. synthetic data distributions

## Technologies Used

- Python (NumPy, Pandas)
- Scikit-learn
- TensorFlow / Keras
- SHAP, LIME
- Facebook Prophet, AutoTS
- Scikit-fuzzy
- Matplotlib, Seaborn

## Dataset

All projects use the **Gold Futures** dataset containing:
- Open, High, Low, Close prices
- Volume
- Price Movement (Up/Down classification target)
