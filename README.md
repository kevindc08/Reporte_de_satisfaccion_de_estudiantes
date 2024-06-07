
# Reporte de Satisfacción Estudiantil.
## Introducción
* Objetivo general.
   - Proporcionar una visión completa del desempeño del personal docente y del trato hacia los estudiantes,mediante un reporte detallado.
* Objetivos especificos.
   1. Realizar ETL (Extraer,Transportar,Cargar).
   2. Analizar los datos de forma general.
   3. Elaborar EDA (Analisis Explorativo de los Datos).
   4. Elaborar un reporte en donde se representan los hallazgos encontrados en el EDA.

* Información básica sobre el dataset y la fuente del mismo.
  - ``SN:`` Número de serie de la pregunta de la encuesta.
  - ``Total Feedback Given:`` Número de estudiantes seleccionados para dar su retroalimentación por curso.
  - ``Total Configured:`` Total de estudiantes en el curso.
  - ``Questions:`` Lista de 20 preguntas de la encuesta.
  - ``Weightage 1:`` Puntuación más baja en la escala.
  - ``Weightage 2:`` Puntuación por debajo del promedio pero mejor que la más baja.
  - ``Weightage 3:`` Puntuación promedio.
  - ``Weightage 4:`` Puntuación por encima del promedio.
  - ``Weightage 5:`` Mejor puntuación.
  - ``Average/Percentage:`` Promedio ponderado mostrado tanto en términos absolutos como en porcentaje.
  - ``Course Name:`` Año actual de la Graduación/Postgrado.
  - ``Basic Course:`` Rama de Graduación/Postgrado.
## 2. Descripción del Dataset
* Este dataset contiene datos recopilados a través de una encuesta de satisfacción realizada a estudiantes. Los datos incluyen respuestas a diversas preguntas relacionadas con la experiencia y satisfacción de los estudiantes en un entorno educativo específico


Pregunta 01
![Pregunta 1](/Images/01.png)

Pregunta 02
![Pregunta 2](/Images/02.png)

Pregunta 03
![Pregunta 3](/Images/03.png)

Pregunta 04
![Pregunta 4](/Images/04.png)

Pregunta 05
![Pregunta 5](/Images/05.png)

Pregunta 06
![Pregunta 6](/Images/06.png)

Pregunta 07
![Pregunta 7](/Images/07.png)

Pregunta 08
![Pregunta 8](/Images/08.png)

Pregunta 09
![Pregunta 9](/Images/09.png)

Pregunta 10
![Pregunta 10](/Images/10.png)

Pregunta 11
![Pregunta 11](/Images/11.png)

Preguunta 12
![Pregunta 12](/Images/12.png)

Pregunta 13
![Pregunta 13](/Images/13.png)

Pregunta 14
![Pregunta 14](/Images/14.png)

Pregunta 15
![Pregunta 15](/Images/15.png)

Pregunta 16 
![Pregunta 16](/Images/16.png)

Pregunta 17
![Pregunta 17](/Images/17.png)

Pregunta 18
![Pregunta 18](/Images/18.png)

Pregunta 19
![Pregunta 19](/Images/19.png)

Ptregunta 20
![Pregunta 20](/Images/20.png)


* Estructura del Archivo
     - El dataset está en formato CSV y tiene 580 filas y 12 columnas, (no se encontraton nulos).

* Uso del Dataset
     - Este dataset puede utilizarse para realizar análisis sobre la satisfacción de los estudiantes con respecto a diferentes aspectos de los cursos. 
     - Se pueden realizar análisis de tendencias, identificar áreas de mejora en los cursos y comparar la satisfacción entre diferentes cursos.


* Herramientas Recomendadas
    - Para trabajar con este dataset, se pueden utilizar herramientas como Python con las bibliotecas Pandas, NumPy y Matplotlib para análisis de datos y visualización.


* Fuente de los Datos
    - Los datos fueron recopilados a través de https://www.kaggle.com/datasets/prasad22/student-satisfaction-survey

# Reporte de satisfacción de estudiantes

## 1.Introduccion

* objetivo general:
    - Proporcionar una visión completa del desempeño del personal docente y del trato hacia los estudiantes, basado en la retroalimentación de los estudiantes, mediante un reporte detallado.
* objetivos especificos:
    1. Realizar ETL (Extraer,Transformar y Cargar) 
    2. Analizar los datos de forma general 
    3. Elaborar EDA (Analisis Exploratorio de los datos)
    4. Elaborar un reporte en donde se presenta los hallazgos encontrados en el EDA
* Informacion basica sobre el Datasets y la fuente del mismo 
    - SN : Número de serie de la pregunta de la encuesta
    - Total Feedback Given : Numero seleccionado de estudiantes de muestra para la retroalimentacion por cursos 
    - Total Configured : Fuerza total del lote por curso básico
    - Questions : Lista de 20 preguntas de la encuesta total
    - Weightage 1 : la calificacion mas baja de la escala
    - Weightage 2 : Mejor que bajo
    - Weightage 3 : Promedio
    - Weightage 4 : bien
    - Weightage 5 : mejor
    - Average/ Percentage : Promedio ponderado en términos absolutos y porcentuales

## 2.Drescripcion del Datasets 
    - Explicación de cada columna del dataset:
    - SN: Número de serie de la pregunta de la encuesta.
    - Total Feedback Given: Número de estudiantes seleccionados para dar su retroalimentación por curso.
    - Total Configured: Total de estudiantes en el curso.
    - Questions: Lista de 20 preguntas de la encuesta.
    - Weightage 1: Puntuación más baja en la escala.
    - Weightage 2: Puntuación por debajo del promedio pero mejor que la más baja.
    - Weightage 3: Puntuación promedio.
    - Weightage 4: Puntuación por encima del promedio.
    - Weightage 5: Mejor puntuación.
    - Average/Percentage: Promedio ponderado mostrado tanto en términos absolutos como en porcentaje.
    - Course Name: Año actual de la Graduación/Postgrado.
    - Basic Course: Rama de Graduación/Postgrado.

    
## 3. Limpieza y Preparación de Datos
- Procedimientos de Limpieza de Datos aplicados
    - Valores Nulos: Imputación o eliminación de valores nulos según la columna afectada.
    - Duplicados: Eliminación de registros duplicados para asegurar integridad de los datos.
- Transformaciones Realizadas
    - Normalización: Escalado de las puntuaciones para un análisis uniforme.
    - Codificación: Transformación de categorías textuales a valores numéricos para facilitar el análisis.
- Justificación de las Decisiones:
    - Las decisiones de limpieza y transformación se basan en la necesidad de obtener un dataset consistente y preparado para análisis estadísticos y visualizaciones gráficas precisas.

## 4. Análisis Exploratorio de Datos (EDA)
- Distribución de las Respuestas por Cada Pregunta
    - Se analizará la frecuencia de cada puntuación por pregunta, utilizando histogramas y gráficos de barras.

- Análisis de las Puntuaciones Obtenidas
    - Promedios y Medianas: Cálculo de las medidas de tendencia central para cada pregunta y curso.
    - Distribuciones: Análisis de las distribuciones de puntuaciones mediante diagramas de caja.
- Comparaciones Entre Cursos y Ramas de Estudio
    - Comparación de las puntuaciones promedio por curso y rama, identificando tendencias y diferencias significativas.

- Visualizaciones Gráficas
    - Uso de histogramas, diagramas de caja y gráficos de barras para ilustrar los hallazgos.

## 5. Análisis Detallado
- Identificación de las Preguntas con Mayor y Menor Puntuación
    - Detección de las preguntas mejor y peor evaluadas por los estudiantes.

- Análisis de Correlación
    - Examen de correlaciones entre diferentes preguntas y entre preguntas y cursos, utilizando matrices de correlación.

- Análisis de Tendencias en las Respuestas
    - Evaluación de si ciertos cursos tienden a obtener puntuaciones más altas o bajas consistentemente.

- Análisis de Diferencias en la Satisfacción
    - Comparación de la satisfacción entre diferentes años de graduación y postgrado.

## 6. Conclusiones y Recomendaciones
- Resumen de los Hallazgos
    - Resumen de los puntos más importantes encontrados durante el análisis.

- Recomendaciones para Mejorar la Satisfacción
    - Sugerencias basadas en el análisis para mejorar la satisfacción estudiantil en los cursos.

- Posibles Áreas de Mejora en la Encuesta
    - Identificación de posibles mejoras en la metodología de la encuesta y en la recolección de datos.

## 7. Anexos
- Código Utilizado para el Análisis
    - Incluye scripts de Python utilizados en el análisis. El código estará disponible en un repositorio de GitHub.

- Tablas y Gráficos Adicionales
    - Material complementario que apoya el análisis realizado.

- Fuentes y Referencias
    - Lista de fuentes y referencias utilizadas en la preparación del reporte.


https://www.kaggle.com/datasets/prasad22/student-satisfaction-survey

