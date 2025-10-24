# Clasificación de Opiniones con Machine Learning

## Descripción del Proyecto

Este proyecto implementa un modelo de **Machine Learning supervisado** para predecir la **opinión de declaraciones textuales** (1 = positiva, 0 = negativa).  
El modelo se entrenó utilizando un conjunto de datos con la variable objetivo `etiqueta`, basada en el contenido textual de las columnas `tweet`, `declaracion` y `palabras_clave`.

El objetivo principal fue construir un **clasificador de texto** capaz de determinar la opinión expresada en una declaración a partir de su contenido.

---

## Proceso de Desarrollo

### Exploración y limpieza de datos
- Se verificó la existencia de valores duplicados y se eliminaron registros repetidos para mejorar la calidad del conjunto de entrenamiento.  
- Se combinaron distintas columnas textuales para obtener una representación más completa de cada declaración.  

### División de datos
Los datos se dividieron en:
- **Entrenamiento:** 90%  
- **Validación:** 10%

---

## Resultados Obtenidos

El modelo alcanzó los siguientes resultados en el conjunto de validación:

- **Accuracy:** 99.74 %  
- **F1-score:** 99.87 %

Estos resultados reflejan un buen desempeño del clasificador, con una adecuada capacidad para identificar opiniones positivas y negativas en los textos analizados.

<img width="725" height="177" alt="image" src="https://github.com/user-attachments/assets/29132228-6ce7-491c-b5de-eaef124b32ab" />

---

## Análisis

El modelo de **Regresión Logística** mostró un rendimiento consistente en la **clasificación de opiniones**.  
Sus resultados evidencian un equilibrio entre **precisión** y **recall**, lo que lo convierte en una base sólida para futuras mejoras o implementaciones en sistemas de análisis de texto.
