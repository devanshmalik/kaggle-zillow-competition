# Kaggle - Zillow's Home Value Prediction Competition 

This repo contains the Jupyter notebook used for the [Kaggle Zillow competition](https://www.kaggle.com/competitions/zillow-prize-1/overview) and is currently a Bronze Medal notebook on Kaggle with a Top 250 Public Score. 

**Highlights of the notebook include:**

- Created end-to-end machine learning pipeline with production level modular code including data exploration, cleaning, feature engineering, picking and tuning candidate algorithms, and model interpretability. 
- Performed extensive data preprocessing of 6M data points including data cleaning, imputation, skewed feature transformations, standard scaling, feature engineering, etc. using Scikit-learn Pipeline for a smoother pipeline workflow
- Trained multiple candidate algorithms and performed extensive hyperparameter tuning including the use of automated tuning packages. Candidate algorithms include Linear Regression (Simple, Lasso, Ridge), Random Forest, and Gradient Boosting Machines (XGBoost, CatBoost, LightGBM) 
- Combined multiple base models using ensemble techniques including Stacking and Voting to obtain more robust models 
- Interpreted complex models (Random Forest, Gradient Boosting Machines) through global and local feature importance analyses using SHAP and Individual Conditional Expectation (ICE) plots 

**Tech Stack: Pandas, Numpy, Matplotlib, Scikit-learn, Hyperopt, Optuna, XGBoost, LightGBM, CatBoost, Shap**


**Note**: Please refer to the [notebook hosted on Kaggle](https://www.kaggle.com/code/devanshm/zillow-end-to-end-ml-workflow-top-250-0-06416/notebook![image](https://user-images.githubusercontent.com/9520975/159796136-e3fabc55-b5b4-4efe-a85c-e421c50fe89d.png)
) to view the outputs from the notebook cells which are unavailable on the Github version of the notebook.
