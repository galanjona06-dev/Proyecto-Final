# Clasificación de tumores mamarios mediante aprendizaje automático

## Descripción del proyecto

Este proyecto utiliza técnicas de ciencia de datos y aprendizaje automático
para clasificar tumores mamarios como malignos o benignos mediante el
conjunto de datos Breast Cancer Wisconsin Diagnostic.

## Objetivo

Evaluar y comparar diferentes modelos de clasificación para identificar
tumores malignos, dando especial importancia al recall de esta clase,
debido a la relevancia de reducir los falsos negativos.

## Dataset

Breast Cancer Wisconsin Diagnostic.

- 569 observaciones.
- 30 características numéricas.
- 212 casos malignos.
- 357 casos benignos.

Codificación de las clases:
- 0: Maligno.
- 1: Benigno.

## Modelos evaluados

- Regresión Logística.
- Naive Bayes.
- Support Vector Machine (SVM).
- Perceptrón Multicapa (MLP).
- Random Forest (modelo adicional).

## Resultados principales

El modelo de Regresión Logística obtuvo los mejores resultados generales:

- Accuracy: 95.61%
- Precision: 91.11%
- Recall: 97.62%
- F1-score: 94.25%
- ROC-AUC: 99.54%

## Tecnologías utilizadas

- Python 3.14.6
- NumPy 2.4.6
- Pandas 3.0.3
- Scikit-learn 1.9.0
- Matplotlib 3.11.0

## Ejecución

1. Instalar las dependencias:

   pip install -r requirements.txt

2. Abrir notebooks/01_analisis_exploratorio.ipynb.
3. Ejecutar las celdas en orden.

## Reproducibilidad

Se utilizó random_state=42 para mantener la reproducibilidad
de las particiones y los experimentos correspondientes.

## Consideraciones

Este proyecto tiene fines académicos y experimentales.
Los resultados no sustituyen un diagnóstico médico profesional.