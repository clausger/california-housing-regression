# 🏡 Modelado Predictivo del Valor de la Vivienda en California

Ejercicio práctico de **Ciencia de Datos** — modelos de regresión.

Predice el valor medio de las viviendas en los distritos de California
(`MedHouseVal`) y compara 4 modelos de regresión:

- **Regresión Lineal Múltiple** (baseline)
- **Regresión Polinómica** (grado 2)
- **Árbol de Regresión completo** (`max_depth=None`)
- **Árbol de Regresión podado** (`max_depth=5`)

Cada modelo se evalúa en el conjunto de testeo con **MAE**, **RMSE** y **R²**.

## ▶️ Abrir en Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clausger/california-housing-regression/blob/main/california_housing_regression.ipynb)

## 📓 Contenido del notebook

El notebook `california_housing_regression.ipynb` está dividido en 8 bloques,
cada uno con su explicación de qué hace y qué dicen los resultados:

| Bloques | Tema |
|---|---|
| 1–2 | Carga de datos y análisis exploratorio (correlación, heatmap, scatter) |
| 3 | División train/test y estandarización |
| 4–5 | Regresión Lineal Múltiple y Polinómica |
| 6 | Árbol de Regresión completo y podado |
| 7–8 | Evaluación comparativa y conclusión |

## 💻 Correr en local (opcional)

En Colab no hace falta instalar nada. Para correrlo en tu máquina:

```bash
pip install -r requirements.txt
jupyter notebook california_housing_regression.ipynb
```

## 📦 Dataset

Se usa `california_housing`, incluido en scikit-learn. Se carga con
`fetch_california_housing()`, no hace falta descargar ningún archivo.
