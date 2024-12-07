# Análisis de Supervivencia del Titanic

Este repositorio contiene un análisis completo del conjunto de datos del Titanic utilizando un modelo de regresión logística. El objetivo es comprender los factores que influyeron en la supervivencia de los pasajeros y construir un modelo predictivo.

---

## Descripción

El conjunto de datos del Titanic es un caso clásico utilizado para explorar los factores de supervivencia durante el hundimiento de este famoso barco. Este proyecto incluye el preprocesamiento de datos, análisis exploratorio y la implementación de un modelo de regresión logística. Los resultados finales se interpretan tanto estadística como inferencialmente para obtener conclusiones significativas.

---

## Funcionalidades

- **Preprocesamiento de Datos**: Limpieza, manejo de valores faltantes y codificación de variables categóricas (e.g., `Sex`, `Embarked`).
- **Análisis Exploratorio**: Visualización de las tasas de supervivencia por género, clase, edad y otras variables clave para identificar patrones importantes.
- **Modelado Predictivo**: Construcción de un modelo de regresión logística para predecir la supervivencia en función de características seleccionadas.
- **Evaluación del Modelo**: Uso de métricas como `precision`, `recall`, `f1-score` y `accuracy` para medir el desempeño del modelo.
- **Resultados e Interpretación**: Identificación de desigualdades en las tasas de supervivencia basadas en género, estatus socioeconómico y edad.

---

## Resultados Clave

- **Género**: El 74% de las mujeres sobrevivieron, en comparación con solo el 19% de los hombres.
- **Clase**: El 62% de los pasajeros de primera clase sobrevivieron, frente al 47% en segunda clase y solo el 24% en tercera clase.
- **Edad**: Los niños menores de 16 años presentaron tasas de supervivencia más altas que los adultos.

---

## Requisitos

Antes de ejecutar el código, asegúrate de tener instaladas las siguientes dependencias:

- Python 3.x
- Librerías:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
