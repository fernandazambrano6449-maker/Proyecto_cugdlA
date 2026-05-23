# **Predicción de posición en la  Fórmula 1**
---
La Formula Uno es considerada una competencia impredecible debido a la gran cantidad de factores que influyen en el desempeño de los pilotos y equipos. Por ello, en este trabajo se emplearon distintos modelos supervisados con el objetivo de desarrollar un modelo capaz de realizar predicciones de clase, yendo más allá de predecir únicamente con la media del conjunto de datos. Para ello, se extrajo información desde la plataforma Kaggle, la cual contenía múltiples datasets relacionados. De estos, se seleccionaron tres conjuntos de datos que posteriormente fueron integrados y procesados para construir un único dataset final utilizado para el análisis.

---
**Referencia**

Vopani. (s. f.). Formula 1 World Championship (1950 - 2024). Kaggele. Recuperado 22 de mayo de 2026, de https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020

## Estructura del repositorio

```
|-- 01_Proyecto_EstadisticaII
  #Importación de los datos en crudo
  #Limpieza de datos
  #Análisis despcriptivo de los datos
  #Intervalo de confianza observaciones pareadas
  #Prueba de independencia $\chi^2$
  #Análisis de varianza

|-- 02_Proyecto_ML
  #Importación del nuevo data frame limpio
  #Análisis exploratorio de los datos
  #Implementación de 5 modelos de machine learning:
    - Regresión logística
    - Decision Tree Classifier
    - Random forest
    - Support vector machine
    - K nearest neighbours
  #Implementación manual de DTC y KNN
  #Desarrollo matemático de DTC y KNN

|-- 03_Proyecto_Complejidad
  #Comparación de complejidad temporal entre el algoritmo de liberia de KNN y manual
  #Comparación de complejidad temporal entre el algoritmo de liberia de DTC y manual
```

