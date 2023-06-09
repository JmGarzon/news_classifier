# Proyecto integrador: MCDA Semestre 1 - Universidad EAFIT
* Michell García Montenegro
* Juan Sebastián Gutiérrez Rivera
* Daniel Gaviria Munera
* Jose Miguel Garzon Vargas

## 1. Organización del directorio
Como el proyecto fue desarrollado en el entorno de Google Colab, 
1. Ubicar el contenido de la carpeta ´src´ en un directorio en Google Drive de su preferencia.
2. Acceder a los documentos compartidos en ´\src\data\data_folder.txt´, y ubicarlos en la carpeta ´data´.

## 2. Preparación de datos
1. Abrir el notebook ´text_prep´.
2. modificar la ruta ´PATH´ por la ruta de la carpeta en la que ubicó el contenido de la carpeta ´src´
3. Ejecutar. Este proceso realiza la preparación del texto de cada noticias de ´noticias.csv´ y lo guarda en el archivo ´noticias_prep.csv´.

## 3. Ejecución del clasificador
1. Abrir el notebook ´news_classifier´.
2. modificar la ruta ´PATH´ por la ruta de la carpeta en la que ubicó el contenido de la carpeta ´src´
3. Ejecutar. Este proceso realiza todo el proceso de representación de la información, topic modeling, entrenamiento y uso del modelo word2vec, clasificación y evaluación del clasificador.