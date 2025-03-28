# ML Pipeline

This folder contains the Jupyter notebook, dataset, and saved model for customer churn prediction.

## Contents

- `ML_Project - Part A.ipynb` — Main notebook with data exploration, training, and evaluation
- `churn.csv` — Customer data used for training
- `rf_model.pkl` — Trained Random Forest model
- `scaler.pkl` — Scaler used to normalize input features (for KNN or prediction API)

## How to Use

1. Open `ML_Project.ipynb` in Jupyter or JupyterLab
2. Run all cells to retrain the model
3. Output files are saved to `.pkl` for use in the FastAPI app


## Graphviz system dependency (not just Python package)

To render Decision Trees using export_graphviz and graphviz.Source, you must also install Graphviz on your system:
* On Ubuntu/Debian: sudo apt-get install graphviz
* On Windows:
  1. Download from: https://graphviz.org/download/
  2. Install it
  3. Add the path to dot.exe (e.g., C:\Program Files\Graphviz\bin) to your System Environment Variables → PATH


## Requirements

Install dependencies using: pip install -r requirements.txt