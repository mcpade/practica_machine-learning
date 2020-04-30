# Práctica: Módulo Machine Learning 101 - Bootcamp KeepCoding - BIG DATA & MACHINE LEARNING

# Machine Learning

En este práctica se utilizan y comparan distintos algoritmos de Machine Learning para ser capaces de predecir el precio de viviendas de Airbnb. El código está desarrollado en Python

Conceptos tratados en esta práctica:

- Librerías **numpy**, **pandas** y **Sklearn** de Python 
- División de datos en train y test
- Limpieza y procesamiento de datos
- Generación de nuevas características
- Análisis exploratorio de variables de tipo numérico. Datos estadísticos, distribuciones
- Tratamiento de outliers
- Análisis exploratorio de variables de tipo categórico
- Análisis exploratorio de variables de tipo booleano
- Codificación de variables categóricas
- Análisis de correlación
- Estandarización y normalización
- Modelos: Uso y comparativa
     - Regresión Lineal
     - Ridge regression
     - Selección de características: Lasso
     - Árbol de regresión
     - Random forest
     - Boosted trees
     - SVR
     

## Enunciado

El objetivo de la práctica es abordar un problema de Machine Learning realista siguiendo la metodología y buenas prácticas explicadas durante las clases teóricas. 

**Problema de regresión: Predecir el precio del airbnb utilizando los datos disponibles**

Se valorará:

• Generación de nuevas características a partir de las existentes

• Codificación de variables

• Análisis exploratorio

• Selección y evaluación del modelo

• Comparativa de distintos algoritmos



## Conjunto de datos

El conjunto de datos escogido es [éste](https://public.opendatasoft.com/explore/dataset/airbnb-listings/export/?disjunctive.host_verifications&disjunctive.amenities&disjunctive.features&q=Madrid&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJ5QXhpcyI6Imhvc3RfbGlzdGluZ3NfY291bnQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20ifV0sInhBeGlzIjoiY2l0eSIsIm1heHBvaW50cyI6IiIsInRpbWVzY2FsZSI6IiIsInNvcnQiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiJyb29tX3R5cGUiLCJjb25maWciOnsiZGF0YXNldCI6ImFpcmJuYi1saXN0aW5ncyIsIm9wdGlvbnMiOnsiZGlzanVuY3RpdmUuaG9zdF92ZXJpZmljYXRpb25zIjp0cnVlLCJkaXNqdW5jdGl2ZS5hbWVuaXRpZXMiOnRydWUsImRpc2p1bmN0aXZlLmZlYXR1cmVzIjp0cnVlfX19XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D&location=16,41.38377,2.15774&basemap=jawg.streets), extraído de Airbnb mediante técnicas de scraping. Dentro de las opciones recomiendo utilizar el extract (“Only the 14780 selected records”), ya que minimiza el tiempo de ejecución y evita problemas de memoria en equipos con menos prestaciones.

El fichero csv que se obtiene en el momento de realizar la práctica se encuentra en la carpeta **data** de este repositorio
