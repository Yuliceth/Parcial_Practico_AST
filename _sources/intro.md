# Parcial Práctico

Este informe presenta el desarrollo y análisis de una serie de ejercicios orientados a la exploración, modelado y predicción de series de tiempo utilizando técnicas estadísticas y de Machine Learning. Se trabajó con datos históricos del precio de Bitcoin, así como con métricas derivadas como el retorno acumulado diario y la volatilidad.

El proceso se dividió en tres secciones principales:

1. Análisis Exploratorio de Datos (EDA): Se realizó una inspección detallada de la serie de tiempo, identificando patrones, tendencias y estacionalidades. Se verificó la existencia de datos faltantes y se aplicaron técnicas de imputación cuando fue necesario. Se implementaron gráficos de velas, histogramas y análisis de estacionariedad mediante pruebas estadísticas.


2. Modelos Estadísticos: Se entrenaron y evaluaron modelos predictivos clásicos como Suavizamiento Exponencial Simple y Doble, ARIMA y GARCH. Se calcularon métricas de error para cada modelo y se analizaron los residuos para verificar su independencia y normalidad.


3. Modelos de Deep Learning: Se implementaron redes neuronales como MLP, RNN y LSTM para la predicción de las series de tiempo. Se construyeron manualmente los pliegues de entrenamiento, validación y prueba, asegurando que respetaran el orden temporal. Se compararon los modelos en términos de error de predicción y se analizaron sus comportamientos mediante gráficos y métricas de desempeño.


Cada resultado obtenido fue interpretado en detalle, proporcionando visualizaciones y análisis que permitieron comprender la dinámica de la serie de tiempo y evaluar la efectividad de cada modelo. A continuación, se presentan los pasos seguidos en cada sección junto con los comentarios derivados de los resultados obtenidos.



```{tableofcontents}
```
