## Predicción de Riesgo Cardiovascular con Lógica Difusa y ML

Este proyecto implementa un sistema inteligente para estimar el riesgo de enfermedad coronaria (CHD) utilizando un sistema difuso basado en reglas médicas, comparándolo con modelos de machine learning como Random Forest y XGBoost.

### Contenido

1. Fuzzy Logic: Se define un sistema de inferencia difuso con variables como obesidad, presión arterial, colesterol LDL, consumo de alcohol/tabaco, entre otros.

2. Random Forest y XGBoost: Se entrenan modelos supervisados para predecir CHD y se ajustan hiperparámetros con GridSearchCV y RandomizedSearchCV.

3. Evaluación: Se comparan los modelos mediante métricas como precisión, recall y matriz de confusión.

### Requisitos

1. Python 3.x

2. scikit-fuzzy, scikit-learn, xgboost, matplotlib, seaborn, pandas, numpy

### Ejecución

1. Subir el archivo cardio.csv

2. Ejecutar el notebook paso a paso

3. Observar resultados de cada modelo y gráficas generadas

### Resultado

1. El sistema difuso permite interpretar reglas clínicas.

2. Random Forest y XGBoost ofrecen mayor precisión predictiva.
