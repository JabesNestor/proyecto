# Predicción de Robos Utilizando Aprendizaje Supervisado

## Introducción

En este análisis, aplicamos técnicas de aprendizaje supervisado para predecir robos utilizando un dataset que contiene información temporal sobre incidentes reportados. El objetivo es construir un modelo que pueda predecir con precisión la ocurrencia de robos basándose en características derivadas de la fecha y hora del incidente.

## Fuente de los Datos

Los datos utilizados en este proyecto fueron obtenidos de la Sociedad Dominicana de Ciencia de Datos y Big Data. Los datos públicos están disponibles en el siguiente enlace: [Sociedad Dominicana de Ciencia de Datos y Big Data - Crime Data](https://bigdatado.org/download/crime-data/).

## Metodología

1. **Preprocesamiento de Datos:**
   - Limpieza y transformación de datos.
   - Manejo de valores faltantes y categorización de variables temporales.

2. **Exploración de Datos (EDA):**
   - Análisis de distribuciones y relaciones entre variables.
   - Visualizaciones para entender patrones temporales y espaciales.

3. **Construcción de Modelos:**
   - Implementación de modelos de Random Forest y Gradient Boosting.
   - Evaluación de los modelos utilizando métricas de precisión.


## Resultados

El modelo de Random Forest tiene una precisión de 54.21%, mientras que el modelo de Gradient Boosting tiene una precisión de 50.70%. Aunque estos resultados son un buen punto de partida, se identificaron varias áreas de mejora para incrementar la precisión y la capacidad predictiva del modelo.

## Conclusiones

En este proyecto, aplicamos técnicas de aprendizaje supervisado para predecir la ocurrencia de robos utilizando datos proporcionados por la Sociedad Dominicana de Ciencia de Datos y Big Data. Los modelos desarrollados demostraron una precisión inicial prometedora. Continuaremos iterando y refinando nuestros modelos para desarrollar una herramienta predictiva más precisa y confiable.

## Próximos Pasos

1. **Validación Cruzada y Ajuste de Hiperparámetros:**
   - Implementar validación cruzada para evaluar la robustez del modelo.
   - Explorar combinaciones de hiperparámetros para optimizar el rendimiento del modelo.

2. **Análisis de Error:**
   - Revisar las instancias mal clasificadas para entender mejor por qué el modelo falla y buscar patrones comunes que puedan ser abordados.

3. **Exploración de Modelos de Ensamblaje:**
   - Probar otros modelos como XGBoost y LightGBM, regresion logistica para comparar su desempeño.

4. **Ingeniería de Características:**
   - Realizar un análisis más profundo de las características temporales y espaciales para mejorar la capacidad predictiva del modelo.



---

Si tienes algún comentario o sugerencia sobre el proyecto, no dudes en ponerte en contacto.
