# Proyecto Final Data Science
## Predicción de precios de autos usados
### Descripción del proyecto

En este proyecto se analiza el dataset de autos usados 'car_price_dataset_medium.csv' que descargue de Kaggle con el objetivo de identificar los factores que influyen en su precio de venta y desarrollar un modelo predictivo.

A través de un Análisis Exploratorio de Datos (EDA) se estudiaron variables como marca, año, kilometraje, tipo de combustible y potencia.
Posteriormente, se entrenó un modelo de regresión y se evaluó su desempeño mediante métricas estándar.

### Objetivo

Analizar el mercado de autos usados y desarrollar un modelo de regresión capaz de predecir el precio de un vehículo a partir de sus características.

### Contexto comercial

El análisis se desarrolla en el contexto de una empresa ficticia dedicada a la comercialización de autos usados mediante una plataforma digital.
El objetivo es optimizar la fijación de precios para mejorar la competitividad y reducir el tiempo de venta.

### Hipótesis

- Existe una relación negativa entre el kilometraje y el precio del vehículo.  
- Los autos más nuevos presentan precios más elevados.  
- Es posible construir un modelo de regresión que prediga el precio con un error aceptable.

### Análisis Exploratorio de Datos (EDA)

Durante el EDA se realizaron los siguientes pasos:
- Exploración inicial del dataset
- Análisis de valores faltantes
- Estadísticas descriptivas
- Visualización de datos:
    - Cantidad de autos por marca
    - Boxplot precio por marca
    - Grafico de torta: de distribucion por tipo de combustible
    - Evolución de la cantidad de autos por año
    - Distribución de tipos de combustible por marca
- Análisis de relaciones entre variables clave

En base a este análisis se seleccionaron las variables más relevantes para el modelado.

### Modelado

Se entrenó un modelo de Regresión Lineal, utilizando:
- Variables numéricas (año, kilometraje, potencia, etc.)
- Variables categóricas codificadas mediante One-Hot Encoding

El dataset fue dividido en conjuntos de entrenamiento y prueba.

### Métricas de evaluación

El modelo fue evaluado utilizando las siguientes métricas:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² (Coeficiente de determinación)

Estas métricas permiten evaluar la precisión y capacidad explicativa del modelo.

### Conclusiones

El modelo de regresión desarrollado logra capturar la relación entre las principales variables y el precio de los autos usados.  
Como trabajo futuro se propone ampliar el dataset y evaluar modelos más complejos.

Los resultados obtenidos indican que el modelo de regresión lineal presenta un desempeño limitado, con errores de predicción elevados y un valor de R² cercano a cero.

Esta situación se explica principalmente por el reducido tamaño del conjunto de datos utilizado, así como por la alta variabilidad de precios y la presencia de variables categóricas con pocas observaciones.

Como trabajo futuro, se propone ampliar el conjunto de datos y evaluar modelos más complejos para mejorar la capacidad predictiva.# Data_Science_I
