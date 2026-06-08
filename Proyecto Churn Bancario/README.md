# Predicción de Churn en Clientes Bancarios

## 📋 Descripción

Modelo de machine learning para predecir qué clientes abandonarán un banco.

## 🎯 Objetivo

Identificar clientes con alta probabilidad de churn y permitir acciones proactivas.

## 📊 Dataset

- 10,127 clientes
- 21 variables (demográficas, económicas, actividad)
- Variable objetivo: attrition_flag (Churn Sí/No)

## 🔧 Técnicas Usadas

- Exploración de datos (EDA)
- Random Forest, ADABOOST, XGBOOST
- Validación cruzada 5-fold
- GridSearchCV para optimización

## 📈 Resultados

**Mejor modelo:** XGBOOST
- Recall: 0.34 (detecta 34% de churners)
- Precision: 0.28
- F1-Score: 0.31

## 🛠️ Tecnologías

Python, pandas, scikit-learn, XGBoost, matplotlib, seaborn

## 📁 Archivos

- `churn_analysis.ipynb` - Notebook completo con código
- `datos/` - Carpeta con datos
- `resultados/` - Gráficos y métricas
