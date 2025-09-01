### 📖 Project Overview
This project focuses on building **machine learning models to predict whether a college basketball player will be drafted into the NBA** based on their season statistics.  

The NBA Draft is a highly anticipated event for players, teams, and fans, making accurate predictions both exciting and valuable. By applying modern ML techniques, we aim to estimate the **probability of a player being drafted**, helping uncover hidden patterns in performance data.  

---

### 🎯 Objectives
- Analyze player statistics to identify draft trends.  
- Build multiple ML models and compare their performance using **AUROC**.  
- Optimize hyperparameters with **Hyperopt** for better predictive accuracy.  
- Track experiments using **Weights & Biases (W&B)**.  
- Interpret model predictions with **LIME** for explainability.  
- Generate Kaggle-ready submission files (`player_id, drafted`).  

---

### 🧪 Models & Experiments
We conducted experiments across several algorithms:
- **Baseline** → Logistic Regression, HistGradientBoostingClassifier  
- **Tree-based** → Random Forest, XGBoost, LightGBM, CatBoost  
- **Ensembles** → LightGBM + CatBoost stacked predictions  

Each experiment is contained in a dedicated notebook (`notebooks/36120-25SP-group31-25414741-AT1-experimentX.ipynb`).  

---

### 📊 Evaluation
- **Metric**: AUROC (Area Under the ROC Curve)  
- **Why AUROC?** It is well-suited for imbalanced classification tasks, focusing on ranking quality rather than just raw accuracy.  
- Cross-validation was applied to ensure robust performance.  

---

### 📂 Deliverables
- **Jupyter Notebooks**: All experiments stored in `notebooks/`.  
- **Model Artifacts**: Trained models saved in `models/`.  
- **Custom Package**: Separate repo with shared utilities & functions, published on TestPyPI.  
- **Final Report**: Summarizes experiments, results, and business implications.  

---

### 📌 Kaggle Competition
- Private Kaggle link: https://www.kaggle.com/t/9b5e26c94f644cc8b812eb4708f3c803  
- Submissions require CSV files with:  
```csv
player_id,drafted
1,0.10
2,0.90
3,0.20

---

### 📂 Repository Requirements

This repository has been set up according to the assignment specifications:

- ✅ Repository created under the required naming convention:  
  **`group31-25414741` (owner: kakadiyadrashti)**  
- ⚠️ Note: Repository is currently **public** instead of private.  
- ✅ Structured using **Cookiecutter Data Science template**  
- ✅ All notebooks stored in `notebooks/` with required naming convention  
- ✅ Model artifacts stored in `models/`  
- ✅ Includes `requirements.txt` and `pyproject.toml` at the root  

**Admin access has been (or will be) granted to the following users:**
- anthony.so@uts.edu.au  
- reasmey.tith@uts.edu.au  
- Natalia.Tkachenko@uts.edu.au  
- Huy.Nguyen-1@uts.edu.au  
- savinay.singh@uts.edu.au  
- TheHai.Bui@uts.edu.au  

---

