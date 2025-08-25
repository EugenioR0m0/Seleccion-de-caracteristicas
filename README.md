# Seleccion-de-caracteristicas

# Wine Quality Dataset – Feature Selection

Este proyecto utiliza un conjunto de datos de vinos tintos descargado del [UCI Machine Learning Repository](https://archive.ics.uci.edu/). El dataset contiene **1,599 observaciones** con 11 variables físico-químicas de cada vino, además de una columna con la **calidad asignada por catadores** en una escala de 0 (muy malo) a 10 (excelente).

## Variables incluidas

- **acidezFija**: gramos de ácido tartárico por decímetro cúbico.  
- **acidezVolatil**: gramos de ácido acético por decímetro cúbico.  
- **acidoCitrico**: gramos de ácido cítrico por decímetro cúbico.  
- **azucarResidual**: gramos de azúcar por decímetro cúbico.  
- **cloruros**: gramos de cloruro de sodio por decímetro cúbico.  
- **dioxidoAzufreLibre**: miligramos de dióxido de azufre libre por decímetro cúbico.  
- **dioxidoAzufreTotal**: miligramos de dióxido de azufre total por decímetro cúbico.  
- **densidad**: gramos por centímetro cúbico.  
- **pH**: nivel de acidez del vino en la escala de pH.  
- **sulfatos**: gramos de sulfato de potasio por decímetro cúbico.  
- **alcohol**: porcentaje de volumen de alcohol en el vino.  
- **calidad**: calificación de la calidad del vino (variable objetivo).  

## Objetivo

El propósito del proyecto es aplicar técnicas de **selección de características** para identificar las variables más relevantes en la predicción de la calidad del vino. Se utilizan métodos de selección secuencial (hacia adelante y hacia atrás) en combinación con un modelo de **regresión lineal múltiple**.  

## Metodología general

1. **Carga y exploración inicial**: revisión de dimensiones y primeras filas del dataset.  
2. **Preparación de datos**: separación en variables predictoras y variable objetivo.  
3. **División de datos**: partición en entrenamiento y prueba (80% – 20%).  
4. **Selección de características**: aplicación de metodologías forward y backward para encontrar subconjuntos óptimos.  
5. **Entrenamiento y evaluación**: ajuste de un modelo de regresión lineal y medición de desempeño con la métrica R².  
6. **Comparación de modelos**: análisis de resultados entre forward y backward para determinar qué enfoque ofrece mejor balance entre simplicidad y capacidad de predicción.

## Tecnologías utilizadas

- **Python**  
- **Pandas** y **NumPy** para manipulación de datos  
- **Scikit-learn** para modelos y métricas  
- **mlxtend** para selección secuencial de características

- [Reporte en ipynb](Seleccion_Caracteristicas.ipynb)
- [Reporte en html](Seleccion_Caracteristicas.html)
- [Base de datos](Datos_Vino_Tinto.csv)
