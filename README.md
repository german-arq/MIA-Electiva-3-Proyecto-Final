# MIA-Electiva-3-Proyecto-Final
Entrega del Proyecto Final de la Electiva de la Maestría en Inteligencia Artificial de la USA

## Contenido del proyecto:
- precios_del_dolar (folder): Archivos con el precio intradiario del dolar (USD/COP) de los 31 días habiles recolectados del ejercicio de AWS Lambda y Glue
- analisis.ipynb: Notebook con la carga y transformación del precio del colar, el analisis de la serie de tiempo, y modelos de prueba (ARIMA, arboles de regresión)
- train_deploy.iypnb: Notebook con el entrenamiento, despliegue como endpoint y prueba del modelo DeepAR para predicción de series de tiempo
- test.json y train.json: Archivos con el formato y estructura requeridos para el entrenamiento del algoritmo DeepAR. Estos archivos fueron subidos a S3 desde donde el modelo si puede tener acceso

