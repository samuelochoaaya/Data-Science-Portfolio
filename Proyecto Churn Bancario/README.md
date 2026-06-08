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
- Recall: 0.8708 (detecta 87% de churners)
- Precision: 0.9529
- F1-Score: 0.9100
- ROC AUC: 0.9923

Se hace hizo un test independiente donde se midió el GAP entre train y test en XGBOOST. Este dio como resultado 0.008, lo cual descarta la posibilidad de sobreajuste. La teoría del sobreajuste aparece por los resultados de los modelos, ya que un ROC AUC 0.99 usualmente está sobreajustado. En este caso simplemente los datos están muy discriminados.

## 🛠️ Tecnologías

Python, pandas, scikit-learn, XGBoost, matplotlib, seaborn

## 📁 Archivos

- `churn_analysis.ipynb` - Notebook completo con código
- `datos/` - Carpeta con datos
- `resultados/` - Gráficos y métricas
