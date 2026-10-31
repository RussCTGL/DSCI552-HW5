# DSCI 552 Homework 5 - Yizhou Lu

Part 1: decision trees as interpretable models on the Acute Inflammations data (multi-label tree, IF-THEN rules, cost-complexity pruning). Part 2: regression on the Communities and Crime data (imputation, correlation and coefficient of variation, least squares, ridge, LASSO, PCR and an L1-penalized XGBoost model, with tuning parameters chosen by cross-validation).

## Layout

```text
data/diagnosis.data, diagnosis.names        Acute Inflammations (UTF-16, tab-separated)
data/communities.data, communities.names    Communities and Crime (CSV, no header, "?" = missing)
notebooks/Lu_Yizhou_HW5.ipynb               the assignment
requirements.txt                            pinned dependencies (Python 3.12)
```

## Run

```text
python -m venv .venv
.venv/bin/pip install -r requirements.txt        # Windows: .venv\Scripts\pip install -r requirements.txt
cd notebooks
jupyter notebook Lu_Yizhou_HW5.ipynb
```

Run the notebook from the `notebooks/` folder. It reads the data with relative paths such as `../data/diagnosis.data` and `../data/communities.data`.
