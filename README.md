# Proyecto 1 - Predicción con Python

## Iván Yosef Maldonado - 14003689

## Video

[Proyecto 1 - Predicción con Python]()

Este proyecto tiene como objetivo implementar y comparar modelos de regresión lineal para predecir el precio de venta de propiedades basándose en diversas características de las mismas. Se utiliza el lenguaje de programación Python y diversas bibliotecas de ciencia de datos y machine learning.

## Librerías Utilizadas

- Numpy: Para el manejo de arrays y matrices.
- Pandas: Para la manipulación y análisis de datos.
- Seaborn y Matplotlib: Para la visualización de datos.
- Scikit-learn: Para implementar el modelo de regresión lineal y calcular el error cuadrático medio.

## Dataset

El dataset contiene información sobre el precio de venta de propiedades y varias características relevantes como la calidad general, el área del primer piso, el número total de habitaciones por encima del sótano, el año de construcción y la longitud de la fachada conectada a la calle. El objetivo es predecir el precio de venta de las propiedades (`SalePrice`).

## Preprocesamiento de Datos

Los datos se dividen en un conjunto de entrenamiento (80%) y un conjunto de validación y prueba (20%). Además, se realiza una exploración inicial para entender la correlación entre el precio de venta y las demás variables del dataset.

## Análisis Exploratorio de Datos (EDA)

Se analiza la correlación de las variables independientes con la variable dependiente (`SalePrice`) y se visualizan estas relaciones mediante gráficos de dispersión.

## Modelo de Regresión Lineal

Se implementa un modelo de regresión lineal desde cero y se entrena con dos variables independientes que mostraron una alta correlación con el precio de venta: la calidad general (`OverallQual`) y el área del primer piso (`1stFlrSF`). Además, se utilizan modelos de regresión lineal de la biblioteca Scikit-learn como comparación.

## Evaluación del Modelo

Se calcula el error cuadrático medio (MSE) para evaluar el rendimiento de los modelos tanto manuales como de Scikit-learn. Esto se realiza en el conjunto de validación y prueba para determinar qué modelo tiene mejor rendimiento en la predicción del precio de venta de las propiedades.

## Conclusiones

El proyecto concluye con una comparación entre los modelos implementados manualmente y los modelos de Scikit-learn, determinando cuál de ellos ofrece mejores predicciones según el error cuadrático medio.

---

Este proyecto es una excelente oportunidad para entender los fundamentos de la regresión lineal y cómo se puede aplicar en problemas reales de predicción de precios. Además, permite comparar la implementación manual de algoritmos de machine learning con las soluciones ya existentes en bibliotecas especializadas como Scikit-learn.
