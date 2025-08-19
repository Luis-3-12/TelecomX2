📊 TelecomX2 – Predicción de Churn

Este notebook implementa un flujo de trabajo de machine learning para analizar datos de clientes de telecomunicaciones y predecir la probabilidad de churn (abandono).

📂 Contenido

Ingesta de datos

Carga de un archivo JSON con la información de clientes.

Higiene de columnas

Normalización de nombres de variables (sin espacios ni puntos, todo en minúsculas).

Conversión de columnas numéricas con coerción suave.

Variable objetivo (Churn)

Transformación a formato binario (0 = no churn, 1 = churn).

Preprocesamiento

Eliminación de columnas irrelevantes.

Análisis de proporción de clientes que hacen churn.

Separación de variables predictoras (X) y objetivo (y).

Detección y tipificación de columnas.

Guardado/carga de dataset intermedio (opcional).

Pipelines de preprocesamiento

Scaled: para modelos sensibles a la escala (Logistic Regression, KNN).

Unscaled: para modelos basados en árboles (Random Forest, Decision Trees).

Split Train/Test

División estratificada para balancear la variable Churn.

Entrenamiento de modelos

Modelos implementados:

Logistic Regression

KNN

Random Forest

Otros árboles de decisión

Evaluación de desempeño

Cálculo de métricas (accuracy, precision, recall, F1).

Matriz de confusión.

Curva ROC y AUC.

⚙️ Requisitos

Python 3.x

Bibliotecas principales:

pandas, numpy

matplotlib, seaborn

scikit-learn

🚀 Uso

Abrir el notebook en Jupyter Notebook o JupyterLab.

Ejecutar las celdas en orden para:

Procesar los datos.

Entrenar los modelos.

Evaluar y comparar resultados.
