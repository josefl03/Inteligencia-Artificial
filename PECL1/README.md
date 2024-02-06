# PECL1. Modelos Lineales

En esta práctica se aborda la predicción dinámica en el ámbito financiero utilizando modelos lineales en Python con datos del S&P500 de Yahoo Finance.

La práctica incluye el preprocesamiento de datos, eliminando observaciones inexistentes y atípicas, y presentando estadísticas descriptivas. Posteriormente, se construye una matriz de variables dependientes e independientes basadas en las rentabilidades de los cinco días anteriores. Se implementa un modelo de regresión lineal múltiple y se evalúa su calidad mediante métricas como MSE, MAE y MAPE.

La evaluación incluye la comparación de predicciones con un paseo aleatorio, utilizando una ventana deslizante de un día y las treinta observaciones anteriores. Además, se calcula la rentabilidad de una estrategia de inversión basada en las predicciones del modelo de regresión lineal múltiple.

En el documento PECL1.ipynb se incluye el código en Python de la práctica, y en PECL1.pptx la presentación utilizada para mostrar el funcionamiento.