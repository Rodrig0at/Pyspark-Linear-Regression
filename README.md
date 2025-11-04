# Predicción del Precio de Cierre del Oro con Machine Learning

Este proyecto implementa , un modelo implementado en PySpark de Regresión Lineal. Utilizando Python, para predecir el precio de cierre del oro a partir de datos históricos de precios y volumen. El objetivo es mostrar el flujo completo de un proyecto de machine learning: desde la preparación de los datos hasta la visualización y análisis de resultados.

## Descripción del proyecto

El modelo utiliza como variables de entrada los precios de apertura, máximo y mínimo. La variable objetivo es el precio de cierre del oro. El proceso incluye la normalización de los datos, el entrenamiento del modelo mediante gradiente descendente y la evaluación de los resultados a través de diferentes visualizaciones.

## Archivos incluidos

- `Portfolio_.ipynb`: Script principal con todo el código del modelo y visualización.
- `Portafolio_A01771433.twb`: Dashboard hecho en tableau, con los datos dados en el csv.
- `Pyspark_Gold_Prediction_Papper.pdf`: Documentación del modelo.
- `Requeriments.txt`: Documentación del modelo.


## Uso

Tienes que descargar de forma local el notebook, así como también el archivo CSV `m15.csv` que su link de acceso se encuentra en el archivo `Requeriments.txt`

El script entrenará un modelo y mostrarán varias gráficas:

- Predicciones vs valores reales
- Grpafico de barras (MSE) y R^2 durante el entrenamiento y prueba
- 

## Requisitos

- Python 3.x
- Pyspark

## Notas sobre los datos

El archivo `m15.csv` pesa 1.05 GB por lo cual no pudo ser incluido dentro del repositorio.

## Autor

Rodrigo Antonio Benítez De La Portilla

---

Si tienes dudas o sugerencias, no dudes en abrir un issue o un pull request.
