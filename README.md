# Ridge vs Lasso Regression – Comparative Study

## Descriere

Acest proiect prezintă un studiu comparativ privind metodele de regularizare Ridge Regression (L2) și Lasso Regression (L1), utilizate pentru reducerea fenomenului de overfitting în modelele de regresie.

Experimentul utilizează setul de date **House Prices – Advanced Regression Techniques**, disponibil pe Kaggle.

## Modele analizate

- Linear Regression – model de referință.
- Ridge Regression – regularizare L2.
- Lasso Regression – regularizare L1.

## Tehnologii utilizate

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Structura proiectului

- `studiu_ridge_lasso.ipynb` – implementarea experimentală.
- `requirements.txt` – bibliotecile necesare.
- `results/` – rezultatele și graficele experimentului.

## Setul de date

Datele pot fi descărcate de aici:

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

Descărcați fișierul `train.csv` și plasați-l în directorul principal al proiectului.

## Executarea proiectului

Instalați bibliotecile necesare:

```bash
pip install -r requirements.txt
```

Deschideți notebook-ul:

```bash
jupyter notebook
```

Executați celulele notebook-ului în ordine.

## Metrici de evaluare

Modelele sunt comparate utilizând:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

## Autor

Daniel Zota

## Scopul proiectului

Proiect realizat în scop academic, pentru analiza comparativă a metodelor de regularizare utilizate în Machine Learning.
