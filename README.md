# <font color='orange'>CUNEF</font>
## `Masters Degree in Data Science`
# El Pulso Político de Twitter Análisis de las Elecciones de Madrid 2023

**Author:**
<p style="text-align:left">Pablo Mazariegos Reviriego - <font color='orange'>pablo.mazariegos@cunef.edu </font>
    

**Resumen:**
En este proyecto de Trabajo Fin de Máster, realizaremos un análisis de sentimiento de los tweets hechos por los 5 candidatos políticos a la presidencia de Madrid durante el período de campaña política que abarcó desde el 12 hasta el 27 de mayo de 2023. Utilizaremos una base de datos recopilada manualmente que contiene los tweets de los candidatos. El objetivo principal de este proyecto es desarrollar modelos de aprendizaje automático que puedan clasificar los tweets según su sentimiento (positivo, negativo o neutral).

El proyecto se organizará en diferentes cuadernos, cada uno enfocado en una etapa específica del proceso:

 1. EDA y Selección/Preparación de variables.
 2. Análisis gráfico y  Word Cloud.
 3. Modelos. Predicción de sentimiento.
 4. Modelos. Predicción de Partido político.
 5. Fine tunning GPT3- Davinci. Predicción de sentimiento.
 6. Fine tunning GPT3- Davinci. Predicción de Partido político.

**Carpeta Data:**
Aqui se encuentran los tweets recopilados en la carpeta raw y los data set procesados en processed.

**Organización de Notebooks:**
Nuestro enfoque para la investigación es estratégico y metodológico, y se encuentra estructurado en una secuencia de seis cuadernos Jupyter, cada uno diseñado con un propósito específico y autónomo pero interconectado dentro de la macroestructura del estudio.

**Notebook 1:**
EDA y Selección/Preparación de variables.

Análisis exploratorio de datos (EDA), introducción del sentimiento con modelo preentrenado, limpieza y transformación de datos.
La adquisición y preparación de datos son los cimientos de cualquier estudio en el campo de la ciencia de datos. En nuestro primer cuaderno, la atención se centra en estas dos tareas fundamentales. Se inicia con el Análisis Exploratorio de Datos (EDA), que nos permite desarrollar una comprensión profunda del conjunto de datos y de sus características inherentes. Durante el EDA, se detectan y examinan patrones, se buscan anomalías y se ponen a prueba hipótesis con la ayuda de estadísticas descriptivas y representaciones gráficas. 
En este cuaderno también se introduce un modelo preentrenado para asignar el sentimiento inicial a los tweets. Posteriormente, se ejecuta una extensa fase de limpieza y transformación de datos, una etapa crucial para garantizar la validez de nuestros futuros análisis. Aquí, los valores faltantes o atípicos son tratados de manera adecuada, las variables se normalizan y se categorizan, y se realizan otras operaciones de preprocesamiento según las necesidades específicas del conjunto de datos.

**Notebook 2:** 
Visualización, WordCloud y estudio de viralidad.

El segundo cuaderno enfatiza la visualización de datos. En esta etapa, generamos representaciones visuales detalladas de los datos con el fin de explorar aún más las tendencias y patrones emergentes en los tweets. Se utilizan WordClouds para ilustrar las palabras y temas más comunes y prominentes en nuestro conjunto de datos. Este cuaderno también incluye un estudio de la viralidad, un análisis dirigido a entender los factores que pueden influir en la propagación masiva de un tweet.

**Notebook 3:** 
Predicción del sentimiento dependiendo de los tweets con modelos SVM, Naive Bayes, XGBoost Classifier, RandomForest, Logistic Regression.

El sexto y último cuaderno emula la estructura del cuaderno 4, repitiendo la tarea de predicción del sentimiento pero con los modelos de aprendizaje automático mencionados anteriormente. Una vez más, los resultados son comparados con los obtenidos utilizando GPT-3, proporcionando un panorama integral de los modelos y técnicas disponibles para este tipo de análisis de sentimiento

**Notebook 4:** 
Predicción del partido político dependiendo de los tweets con modelos SVM, Naive Bayes, XGBoost Classifier, RandomForest, Logistic Regression.

El quinto cuaderno repite el análisis del cuaderno 3, pero esta vez recurriendo a varios modelos de aprendizaje automático tradicionales: SVM, Naive Bayes, XGBoost Classifier, RandomForest y Logistic Regression. Los resultados obtenidos a partir de estos modelos se comparan con los del modelo GPT-3 para proporcionar una visión más completa y equilibrada de las diferentes herramientas disponibles para realizar esta tarea.

**Notebook 5:**
Predicción del sentimiento dependiendo de los tweets con GPT-3.

Similar al tercer cuaderno, el cuarto cuaderno implementa el modelo GPT-3 para predecir el sentimiento político expresado en un tweet. Se sigue un proceso similar de entrenamiento, evaluación y análisis de los resultados obtenidos.

**Notebook 6:**
Predicción del partido político dependiendo de los tweets con GPT-3.

El tercer cuaderno se dedica a la aplicación del modelo GPT-3 para predecir la afiliación política del autor de un tweet. Con los datos debidamente preparados, el modelo GPT-3 se entrena y evalúa, y se realiza un análisis detallado de los resultados.



