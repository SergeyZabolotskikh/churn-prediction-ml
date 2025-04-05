# ML Pipeline

This folder contains the Jupyter notebook, dataset, and saved model for customer churn prediction.

## Contents

- `ML_Project - Part A.ipynb` — Main notebook with data exploration, training, and evaluation
- `churn.csv` — Customer data used for training
- `random_forest_best_model.joblib` — Trained Random Forest model
- `decision_tree_best_model.joblib` - Decision Tree model
- `best_knn_model.joblib` - KNN model
- `scaler.joblib` — Scaler used to normalize input features (for KNN or prediction API)
- `churn.json` - Data to predict, loaded to MongoDB first of all
- `ML Project - Part B.ipynb` - Notebook with data prediction for churn.json, after applying ML, the data is exported into csv in the same format as churn.csv 
- 
## How to Use

1. Open `ML_Project - Part A.ipynb` in Jupyter or JupyterLab
2. Run all cells to retrain the model
3. Output files are saved to `.joblib` for use in the FastAPI app
4. Load churn.json into MongoDB
5. Execute `ML_Project - Part B.ipynb` in Jupyter or JupyterLab

## Graphviz system dependency (not just Python package)

To render Decision Trees using export_graphviz and graphviz.Source, you must also install Graphviz on your system:
* On Ubuntu/Debian: sudo apt-get install graphviz
* On Windows:
  1. Download from: https://graphviz.org/download/
  2. Install it
  3. Add the path to dot.exe (e.g., C:\Program Files\Graphviz\bin) to your System Environment Variables → PATH


## Requirements

Install dependencies using: pip install -r requirements.txt