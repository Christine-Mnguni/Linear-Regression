# 🏡 Ames Housing Price Prediction — Linear Regression Analysis

This project applies linear regression techniques using Python to explore how two features — **above grade living area (`Gr_Liv_Area`)** and **garage area (`Garage_Area`)** — impact the sale prices of homes in the Ames Housing dataset.

---

## 📌 Objective

To predict housing prices (`SalePrice`) using `Gr_Liv_Area` and `Garage_Area` as key predictors and to understand their relationships through data visualization and correlation analysis.

---

## 🧰 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error
