# Reporte de satisfacción de estudiantes
## 1. Introducción
* Objetivo general. 
    - Proporcionar una vision completa del desempeño del personal docente y del trato hacia los estudiantes,mediante un reporte detallado
* Objetivos especificos
    1. Realizar ETL (Extraer,Trasformar,Cargar).
    2. Analizar los datos de forma general.
    3. Elaborar EDA (Analisis Exploratorio de los datos).
    4. Elaborar un Reporte en donde se representan los hallazgos encontrados en el EDA.
* Información básica sobre el dataset y la fuente del mismo.
    - SN: Número de serie de la pregunta de la encuesta.
    - Total Feedback Given: Total de comentarios dados
    - Total Configured: Fuerza total del lote por curso básico.
    - Questions: Pregunta de la encuesta.
    - Weightage 1: Escala baja.
    - Weightage 2: Mejor que bajo.
    - Weightage 3: Promedio.
    - Weightage 4: bien.
    - Weightage 5: mejor.
    - Average/ Percentage: Promedio ponderado en términos absolutos y porcentuales.
    - Course Name: Nombre del curso
    - Basic Course: Curso Básico.
## 2. Descripción del Dataset
    - Lo que podemos observer del dataset 

## 3. Limpieza y Preparación de Datos
    - Procedimientos de Limpieza de Datos
    - Valores Nulos: Imputación o eliminación de valores nulos según la columna afectada.
    - Duplicados: Eliminación de registros duplicados para asegurar integridad de los datos.
    - Transformaciones Realizadas
    - Normalización: Escalado de las puntuaciones para un análisis uniforme.
    - Codificación: Transformación de categorías textuales a valores numéricos para facilitar el análisis.
    - Justificación de las Decisiones
    - Las decisiones de limpieza y transformación se basan en la necesidad de obtener un dataset consistente y preparado para análisis estadísticos y visualizaciones gráficas precisas.

## 4. Análisis Exploratorio de Datos (EDA)
    *Distribución de las Respuestas por Cada Pregunta
    -Se analizará la frecuencia de cada puntuación por pregunta, utilizando histogramas y gráficos de barras.

Análisis de las Puntuaciones Obtenidas
Promedios y Medianas: Cálculo de las medidas de tendencia central para cada pregunta y curso.
Distribuciones: Análisis de las distribuciones de puntuaciones mediante diagramas de caja.
Comparaciones Entre Cursos y Ramas de Estudio
Comparación de las puntuaciones promedio por curso y rama, identificando tendencias y diferencias significativas.

Visualizaciones Gráficas
Uso de histogramas, diagramas de caja y gráficos de barras para ilustrar los hallazgos.

5. Análisis Detallado
Identificación de las Preguntas con Mayor y Menor Puntuación
Detección de las preguntas mejor y peor evaluadas por los estudiantes.

Análisis de Correlación
Examen de correlaciones entre diferentes preguntas y entre preguntas y cursos, utilizando matrices de correlación.

Análisis de Tendencias en las Respuestas
Evaluación de si ciertos cursos tienden a obtener puntuaciones más altas o bajas consistentemente.

Análisis de Diferencias en la Satisfacción
Comparación de la satisfacción entre diferentes años de graduación y postgrado.

6. Conclusiones y Recomendaciones
Resumen de los Hallazgos
Resumen de los puntos más importantes encontrados durante el análisis.

Recomendaciones para Mejorar la Satisfacción
Sugerencias basadas en el análisis para mejorar la satisfacción estudiantil en los cursos.

Posibles Áreas de Mejora en la Encuesta
Identificación de posibles mejoras en la metodología de la encuesta y en la recolección de datos.

7. Anexos
Código Utilizado para el Análisis
Incluye scripts de Python utilizados en el análisis. El código estará disponible en un repositorio de GitHub.

Tablas y Gráficos Adicionales
Material complementario que apoya el análisis realizado.

Fuentes y Referencias
Lista de fuentes y referencias utilizadas en la preparación del reporte.
https://www.kaggle.com/datasets/prasad22/student-satisfaction-survey