# Diamond Price Prediction (ML)

End-to-end notebook for predicting diamond prices using classical ML (EDA → feature engineering → model training).  
- Ordinal encoding for cut, color, clarity  
- Scaling of numerical attributes (carat, depth, table, dimensions)  
- Models: Linear Regression, Random Forest (via scikit-learn pipelines)  
- Metric: R² ≈ 0.9 on holdout 

## Quickstart
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook DiamondPricePrediction.ipynb
```

## Tech
- Python, NumPy, Pandas, scikit-learn, Matplotlib, Seaborn, Jupyter

## Repo layout
```
DiamondPricePrediction.ipynb  # main notebook
```

## License
MIT
