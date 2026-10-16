# ECON 5360 — Statistical Modeling

This folder contains materials for exploring statistical modeling in Python, including linear and logistic regression.

## Contents

- `Lecture04_Statistical_Modeling_10_15.ipynb` — Jupyter notebook with a Pandas refresher and examples using regression and classification models.
- `diabetes.csv` — Pima Indians Diabetes dataset with 768 observations. `Outcome` is the binary target; the other columns are predictor variables.
- `pima.zip` — Compressed copy of `diabetes.csv`.
- `requirements.txt` — Core Python dependencies: statsmodels, NumPy, pandas, and seaborn.

## Getting started

Use Python 3 and install the listed packages:

```bash
python -m pip install -r requirements.txt
```

The notebook also imports scikit-learn, Matplotlib, Plotly, and SciPy, and requires Jupyter to run. Install those if they are not already available:

```bash
python -m pip install jupyter scikit-learn matplotlib plotly scipy
```

Start Jupyter from this folder and open the notebook:

```bash
jupyter notebook
```

Keep `diabetes.csv` in this folder when running notebook cells that load the dataset.
