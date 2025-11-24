# Hull Tactical Market Prediction — ML Time-Series Modeling

## Purpose of Analysis
This project investigates whether daily S&P 500 excess returns can be predicted using machine learning, challenging the Efficient Market Hypothesis (EMH). Using Ridge Regression, Random Forest, AdaBoost, and Gradient Boosting, the goal is to model forward returns, evaluate performance using time-series cross-validation, and determine whether financial signals contain exploitable predictive patterns.  
The analysis applies ISM 6419 concepts including ensemble methods, boosting algorithms, model evaluation, and proper non-leaking time-series validation.

---

## Project Overview
- Dataset: Hull Tactical Market Prediction (Kaggle)
- Target: `market_forward_excess_returns`
- Features: 197 engineered financial indicators including market dynamics, macroeconomic signals, volatility metrics, sentiment proxies, valuation ratios, and momentum features.
- Models used:
  - Ridge Regression  
  - Random Forest  
  - AdaBoost  
  - Gradient Boosting  
- Evaluation Metrics:
  - R², MAE, RMSE  
  - Fold-by-fold time-series performance  
- Key Finding: All models produced negative R² scores, supporting the Efficient Market Hypothesis (EMH). Boosting models performed best among the four.
- - Dataset: Hull Tactical Market Prediction (Kaggle) — [competition page](https://www.kaggle.com/competitions/hull-tactical-market-prediction)


---

##  Repository Structure
project/
│
├── data/
│ └── readme.txt
│
├── notebooks/
│ └── HullTactical_TimeSeriesModeling.ipynb
│ └── readme.txt
│
└── README.md

###  /data
Contains dataset documentation. The raw Kaggle dataset cannot be included due to licensing restrictions.

###  /notebooks
Contains the full modeling notebook implementing:
- Time-series CV  
- Ridge Regression  
- Random Forest  
- AdaBoost  
- Gradient Boosting  
- Ensemble averaging  
- Feature importance plots  

---



