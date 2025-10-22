# Tarea-2-machine-learning: Bosón de Higgs

El 4 de julio de 2012, tras décadas de teoría y experimentación, el CERN descubrió el bosón de Higgs. Desde entonces, los colisionadores de partículas pretenden estudiarlo, generando una gran cantidad de datos acerca de la energía faltante, energía, momentum, rapidez transversal y azimutal, entre otras, para cada partícula, y se cataloga si se identificó el bosón de Higgs usando la etiqueta: 0 (no hay señal) y 1 (si hay señal). En esta tarea trabajamos con una versión simplificada de los datos simulados del bosón de Higgs del desafío de Kaggle. 

### Trabajo realizado

En esta tarea se aplicaron diversas técnicas de machine learning con enfoque en el tratamiento de datos desbalanceados.

-Exploración de datos: Se detectó un **fuerte desbalance** en las etiquetas, predominando la clase `0`. Dado el desbalance, se concluyó que métricas como **recall**, **precision**, y especialmente la **F1-score** son más apropiadas que la accuracy.

-Visualización de Features

-Implementación de árboles de decisión: Se reportaron el **promedio y desviación estándar de los scores**.
-Implementación de SVMs

-Optimización de hiperparámetros: Se usó solo el 5% de los datos (aleatorizados) para acelerar la búsqueda.

-Manejo de clases imbalanceadas: Se implementó SMOTE (Synthetic Minority Over-sampling Technique) para generar muestras sintéticas de la clase minoritaria

-Conclusiones: SVM con parámetros optimizados y SMOTE mostró el mejor rendimiento en métricas como F1-score, en comparación a los otros modelos.

### Usos
Primer acercamiento al fit de modelos de machine learning en data sets imbalanceados

### Dataset
Los datos utilizados provienen del desafío de Kaggle "Higgs Boson Machine Learning Challenge". Más información [aquí](https://www.kaggle.com/c/higgs-boson).

### Contacto
- justine.haefele@usm.cl
- joseph.dabre@usm.cl
