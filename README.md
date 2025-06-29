Proyecto de Predicción de Flujo de Efectivo - TFM 2025

Este repositorio contiene los ficheros y recursos necesarios para el desarrollo del Trabajo de Fin de Máster enfocado en la predicción de flujo de efectivo mediante algoritmos de Machine Learning.

Descripción de Ficheros Principales

A continuación se detalla el propósito de cada fichero en el directorio raíz:

"TrabajoFinMaster2025.ipynb": Es el notebook principal del proyecto. Contiene todo el proceso de análisis de datos, preprocesamiento, entrenamiento de los modelos de Machine Learning, evaluación y generación de los ficheros de resultados.

"ModelCashFlowPrediction.pkl": Este es el modelo de Machine Learning ya entrenado y guardado (serializado) usando pickle. Debido a su tamaño, no ha podido incluirse en el repositorio. Sin embargo, puede ser generado localmente ejecutando el notebook TrabajoFinMaster2025.ipynb.

"PreTremplate01.csv": Fichero CSV que contiene los datos en su estado original o semi-original, antes de las principales transformaciones y preprocesamiento para el modelo.

"PreTremplate01_Transform.csv": Contiene los datos del fichero PreTremplate01.csv después de haber sido procesados, limpiados y transformados. Este es el dataset que probablemente se utiliza para entrenar y evaluar el modelo.

"CashFlowPredictions.csv": Un fichero CSV que almacena los resultados de las predicciones hechas por el modelo. Incluye columnas como el mes, tipo de documento y la predicción generada. Es utilizado por el dashboard Dashboard Predicciones.html.

"VariablesCategoricasEncoder.csv": Almacena la codificación (mapeo) de las variables categóricas. Es crucial para convertir las categorías de texto a un formato numérico que el modelo pueda entender y viceversa.

Directorio Visualizacion

Esta carpeta contiene los ficheros necesarios para generar los dashboards interactivos que muestran los resultados del proyecto.

"Visualizacion/Comparativa de Algoritmos.html": Un dashboard interactivo que presenta una comparación detallada del rendimiento de los diferentes algoritmos de clasificación probados. Muestra métricas como Accuracy, AUC, F1-Score, etc., en gráficos y tablas. Se recomienda descargar este fichero html y abrirlo en un navegador web para una mejor experiencia.

"Visualizacion/Resultados.json": Fichero en formato JSON que contiene los datos de rendimiento de cada algoritmo evaluado. Es la fuente de datos para el dashboard Comparativa de Algoritmos.html.

"Visualizacion/style.css": La hoja de estilos CSS que define la apariencia visual de los dashboards HTML. Proporciona un diseño consistente y profesional para todas las visualizaciones.
