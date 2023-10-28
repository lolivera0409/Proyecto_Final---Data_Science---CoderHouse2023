# Géneros de videojuegos y su éxito en ventas: Un Análisis Regional
Proyecto de Graduación del curso Data Science 2023 de CoderHouse, Comisión 41875.
Desarrollado a lo largo del año 2023 en múltiples fases.
Tiene como objetivo evaluar la influencia del género de los videojuegos en diversas regiones y su impacto en las ventas.

# Prerequisitos

Para la realización de este repositorio, se utilizó Google Collab con Python3 y las siguientes paqueterías:

  • [Pandas] (https://pandas.pydata.org/)
  
  • [NumPy] (https://numpy.org/)
  
  • [Tabulate] (https://pypi.org/project/tabulate/)
  
  • [Matplotlib] (https://matplotlib.org/)
  
  • [Scikit-Learn] (https://scikit-learn.org/stable/)
  
Para instalar las paqueterías mencionadas previamente, se utilizan los siguientes comandos en la Terminal del Sistema (CMD), o directamente desde Google Collab:
  
  • pip install pandas
  
  • pip install numpy
  
  • pip install tabulate
  
  • pip install matplotlib
  
  • pip install scikit-learn
  

La paquetería "Warnings" viene por defecto incluida con Python, por lo que no se le realiza ninguna instalación.

# Estructura del proyecto

Este proyecto cuenta con los siguientes archivos:

  • Documentación_Proyecto (Documento en formato PDF, una guía de qué ideas se tuvo al implementar el código y una suma de los resultados obtenidos)
  
  • Notebook_Proyecto (La versión final del código del proyecto, mostrando solo lo conseguido de forma rápida, sin toda la búsqueda de hiperparámetros y modelos)
  
  • Pruebas_Notebook_Proyecto (Pruebas conjuntas del código. Contiene la búsqueda de hiperparámetros, la búsqueda de diferentes modelos y algunas notas extra, paqueterías no usadas, etc)
  

Datos a destacar:

  • Documentación_Proyecto contiene enlaces que llevan tanto al dataset, como a oportunidades de mejora para el mismo, además de las conclusiones obtenidas
  
  • Notebook_Proyecto toma aproximadamente 120 segundos en correr
  
  • Pruebas_Notebook_Proyecto tomó aproximadamente 28.000 segundos en correr. Esto es debido a la selección de hiperparámetros. Para evitar que se ejecute el código por accidente, las líneas de código de a búsqueda de hiperparámtros fueron excluidos (marcados como comentarios)

# ¿Cómo funciona?

El código dentro de Notebook_Proyecto utiliza un dataset de Kaggle (Video_Games_Sales), realizando una variedad de areglos a las variables ya existentes, además de crear algunas sintéticas para la ayuda del cálculo de ciertas métricas.

Posterior a eso, el dataset resultante se utiliza para verificar la correlación de variables, se grafican resultados o resumen en tablas para poder entender los datos más para una visión empresarial.

Finalmente, se entrenan modelos de Machine Learning (principalmente GradientBoosting), con el objetivo de intentar crear un modelo capaz de predecir el género de un videojuego, o si el mismo puede llegar a ser un éxito.
