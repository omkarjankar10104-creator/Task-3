# Assignment 4: End-to-end data preparation

Dataset: CarDekho used cars, https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

No model is trained. The notebook stops at a clean, model-ready matrix.

## Before and after

| Stage | Rows | Columns | Missing values | Duplicate rows |
|---|---|---|---|---|
| Raw file | 8128 | 12 | 878 | 1202 |
| After clean() | 6926 | 13 | 848 | 0 |
| Final matrix | 6926 | 22 | 0 | 493 |

## Files

- assignment4_endtoend.ipynb
- cleaned_data.csv
- pipeline.joblib
