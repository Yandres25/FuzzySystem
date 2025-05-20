Predicción de Riesgo Cardiovascular con Lógica Difusa y ML

Este proyecto implementa un sistema inteligente para estimar el riesgo de enfermedad coronaria (CHD) utilizando un sistema difuso basado en reglas médicas, comparándolo con modelos de machine learning como Random Forest y XGBoost.
Contenido

    Fuzzy Logic: Se define un sistema de inferencia difuso con variables como obesidad, presión arterial, colesterol LDL, consumo de alcohol/tabaco, entre otros.

    Random Forest y XGBoost: Se entrenan modelos supervisados para predecir CHD y se ajustan hiperparámetros con GridSearchCV y RandomizedSearchCV.

    Evaluación: Se comparan los modelos mediante métricas como precisión, recall y matriz de confusión.

Requisitos

    Python 3.x

    scikit-fuzzy, scikit-learn, xgboost, matplotlib, seaborn, pandas, numpy

Ejecución

    Subir el archivo cardio.csv

    Ejecutar el notebook paso a paso

    Observar resultados de cada modelo y gráficas generadas

Resultado

    El sistema difuso permite interpretar reglas clínicas.

    Random Forest y XGBoost ofrecen mayor precisión predictiva.
