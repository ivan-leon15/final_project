# Análisis de Eficiencia de Operadores en Servicio Telefónico Virtual
## Descripción del Proyecto
Este proyecto tiene como objetivo analizar la eficiencia de los operadores en un servicio de telefonía virtual utilizando datos relacionados con el total de llamadas, duración promedio de llamadas, llamadas perdidas, tiempo promedio de espera, y la clasificación de las llamadas en entrantes y salientes.

## Problema a Resolver
El objetivo principal es identificar operadores ineficaces basándose en tres criterios:

- Llamadas perdidas: Un número elevado de llamadas entrantes perdidas.
- Tiempo de espera: Tiempo prolongado de espera en las llamadas entrantes.
- Llamadas salientes: Un número reducido de llamadas salientes en caso de que el operador deba realizarlas.
## Hipótesis
Se plantea la hipótesis de que existe una diferencia significativa en la cantidad de llamadas perdidas entre los operadores eficientes y no eficientes. Se ha realizado una prueba A/B para evaluar esta hipótesis.

## Lenguaje de Programación: Python
## Bibliotecas de Python:
- pandas para la manipulación de datos.
- matplotlib y seaborn para la visualización de los datos.
- scikit-learn para la evaluación y modelado de datos.
- scipy para las pruebas estadísticas.
## Software de Visualización: 
Tableau para crear gráficos circulares, de barras y otros visuales más avanzados.
Jupyter Notebook para la implementación del código y documentación del análisis.
## Metodología
Transformación de Datos:

Estandarización y normalización de las variables relevantes.
Categorización de operadores en "eficientes" e "ineficientes" según los criterios mencionados.
## Análisis Exploratorio de Datos:

Generación de gráficos como diagramas de dispersión, histogramas y gráficos de barras para entender la distribución de las variables.
Mapas de calor para identificar correlaciones entre las variables.
## Prueba A/B:

Se utilizó una prueba t de dos muestras para comparar la cantidad de llamadas perdidas entre los operadores eficientes y los no eficientes.
## Modelado de Datos:

Implementación de modelos de regresión logística y árboles de decisión para predecir la eficiencia de un operador basado en los datos.
Evaluación de los modelos mediante métricas como precisión, recall y accuracy.
## Conclusión:

El análisis reveló una diferencia significativa en las llamadas perdidas entre los operadores eficientes e ineficientes, lo que llevó a la validación de la hipótesis inicial.
El modelo de regresión logística demostró ser eficaz para la clasificación de los operadores.
## Resultados y Conclusiones
Resultados de la Prueba A/B: La prueba t indicó que existe una diferencia significativa entre los operadores eficientes e ineficientes respecto a las llamadas perdidas, lo que justifica la propuesta de acciones para mejorar la eficiencia en los operadores clasificados como ineficaces.
Modelos Predictivos: La regresión logística y el árbol de decisión mostraron resultados satisfactorios para predecir la eficiencia del operador.
## Visualización de Datos
A través de los gráficos generados en Python y Tableau, se presentaron visualizaciones que demuestran las diferencias entre los grupos de operadores, lo que facilita la identificación de las áreas de mejora.
