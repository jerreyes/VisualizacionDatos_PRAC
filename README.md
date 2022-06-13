# VisualizacionDatos_PRAC
Repositorio para los archivos y visualizaciones para la Practica de Visualización de datos

## Limpieza de datos

En primer lugar, se ha realizado la limpieza de datos para el dataset propuesto que se encuentra en la plataforma kaggle: https://www.kaggle.com/datasets/zynicide/wine-reviews?datasetId=1442&sortBy=voteCount. Se han realizado diversas operaciones para tratar los registros con datos nulos, se ha realizado tarea de imputacion de valores a través de la media de la columna a imputar. Por otro lado, variables con muchos registros categoricos vacios se han eliminado para de esta manera obtener un dataset con toda la información 'rellenada' posible, que no faltara ningún dato para que sea más sencillo trabajar con el en las representaciones de Tableau.

    original dataset = https://drive.google.com/file/d/1nFiRmUAGkPGdKgO1y-3wQ1qRL1TCLBns/view?usp=sharing
    clean_dataset = https://drive.google.com/file/d/1ESBfjs0_9OFt1RZYnCCCmJ_eYzmlwIFZ/view?usp=sharing

## Visualizaciones - Tableau

Una vez obtenido el dataset_clean.csv, se procede a introducirlo en la plataforma Tableau public para comenzar a elaborar las diferentes representaciones a partir del mismo, con el objetivo de llegar a responder diversas preguntas relacionadas o enfocadas en la visualización de datos:

 * ¿Como se distribuyen las valoraciones según los diferentes paises?
 * ¿Cuales son los paises con una puntuacion en su valoración mas elevada?
 * Cual es la distribución de los vinos según su precio y su puntuación?
 * ¿Cúales son las bodegas más populares?
 * ¿Que usuarios (twitter) són los más activos? Aquellos que han realizado más reviews
 * ¿Cual es la variedad de vino que más valoran los usuarios?
 * ¿Cual es la variedad de vino más caro?


    Visualizaciones:
    https://public.tableau.com/views/PRACTICA_16551449974310/Cartograma-MediaPuntuaciones?:language=es-ES&:display_count=n&:origin=viz_share_link

## Diseño

En cuanto al diseño de las visualizaciones se ha procurado aplicar una paleta de colores relacionada con el tema del dataset, en este caso, se trata de un dataset sobre vinos y la valoracion de algunos usuarios en diferentes bodegas, por ello se ha obtado en algunas visualizaciones por una paleta fucsia/morada ya que va acorde con el tema, por otro lado en alguna que otra visualización se ha dejado el color predeterminado (azul), ya que en dicho caso se representaba la indidencia de los usuarios de twitter el cual el color predominante es el azul.
