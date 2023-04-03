
# Parcial inteligentes 2 

Nestor Ortiz
<br/>
Hector rubio

E
ste proyecto utiliza cuatro algoritmos de aprendizaje automático para clasificar datos:

K-Nearest Neighbors (KNN)
Naive Bayes
Árbol de Decisión
Random Forest
K-Nearest Neighbors (KNN)
El algoritmo KNN se utilizó para clasificar los datos utilizando la distancia Euclidiana. Se realizaron pruebas con diferentes valores de K para obtener el mejor rendimiento en la clasificación.

Naive Bayes
El algoritmo Naive Bayes se utilizó para clasificar los datos utilizando la probabilidad condicional. Se utilizó el clasificador Multinomial Naive Bayes para manejar datos discretos y se realizó un ajuste de Laplace para evitar probabilidades nulas.

Árbol de Decisión
El algoritmo Árbol de Decisión se utilizó para clasificar los datos utilizando la selección de características y la división de nodos basada en la entropía. Se realizaron pruebas con diferentes profundidades máximas del árbol para obtener el mejor rendimiento en la clasificación.

Random Forest
El algoritmo Random Forest se utilizó para clasificar los datos utilizando un conjunto de árboles de decisión. Se realizaron pruebas con diferentes números de árboles para obtener el mejor rendimiento en la clasificación.

Resultados
Se evaluó el rendimiento de los cuatro algoritmos utilizando la precisión, el recall y el F1-score. Los resultados se pueden encontrar en el archivo de resultados adjunto.


#Nota  -> al dataset toco agregarle el nombre de las columnas ya que no tenian 

en general antes de implementar un algoritmo se hizo este tratamiento a los datos 
1. primero se cargaron las librerias necesarios 
1. luego se cargo el dataset que es encuentra en el repositorio como  ```Myocardial infarction complications.csv```
1. se cambio ? por NaN para poder cuantos datos hacian falta en el dataset
1. se eliminaron algunas columnas y filas ya que no aportaban al modelo
1. se aplico hizo imputación para tratar los datos faltantes
1. luego se aplico cada algoritmo