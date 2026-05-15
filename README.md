# Proyecto 1: LSA con SVD aplicado a reseñas de Counter-Strike en Steam

Integrante: Giousé Nobizelli

El objetivo del proyecto es aplicar LSA mediante la SVD sobre un corpus de reseñas de Steam para descubrir la estructura temática latente, representando tanto términos como documentos en un espacio de baja dimensión.

## Estructura del Repositorio

* `Notebook Proyecto.ipynb`: Jupyter Notebook (desarrollado en Google Colab) que contiene todo el código del proyecto, preprocesamiento del texto, análisis de frecuencias, aplicación de TF-IDF, cálculo de la SVD, gráficos de valores singulares/energía acumulada y visualizaciones 2D.
* `Informe proyecto 1 algebra.pdf`: Informe que detalla el marco metodológico, la construcción de la matriz textual, el análisis e interpretación de las componentes principales y las conclusiones obtenidas.
* `counterstrike_reviews.csv`: Dataset con todas las reviews de los juegos que contengan el nombre "counter-strike".
* `counter_strike_solo.csv`: Dataset de solo las reviews de el juego "Counter-strike".

## Requisitos e Instalación

Para ejecutar el código de este proyecto localmente, se necesita Python 3 y las librerias: numpy, pandas, matplotlib y scikit-learn.

Como el archivo "counter_strike_solo.csv" ya se encuentra en el repositorio, el punto del notebook "Preparación del archivo de datos" es opcional ejecutarlo, ya que ese apartado es solo para crear el mismo archivo .csv. Por lo que si se descarga el archivo "counter_strike_solo.csv", es posible saltarse ese punto y empezar desde la celda con los Imports hacia abajo 
