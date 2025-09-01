### 📖 Project Overview
Predict whether a college basketball player will be drafted into the NBA using season stats.  
We train several machine learning models and evaluate them with **AUROC**.  
The best model generates a Kaggle-ready submission with probabilities for each `player_id`.

**What’s inside**
- Models: Logistic/HistGradientBoosting, Random Forest, LightGBM, CatBoost, XGBoost
- Cross-validation & hyperparameter tuning
- Experiment tracking (W&B) and model interpretability (LIME)
- Reproducible notebooks and saved model artifacts

**How to run (quick)**
1) `pip install -r requirements.txt` (Python **3.11.4**)  
2) `jupyter lab` → open a notebook in `notebooks/` and run all cells  
3) Export predictions as CSV and submit to Kaggle

**Kaggle submission format**
```csv
player_id,drafted
1,0.10
2,0.90
3,0.20
