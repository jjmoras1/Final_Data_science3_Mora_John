# Análisis de Sentimiento sobre la Salud Mental

Este proyecto realiza un análisis de sentimiento sobre la salud mental utilizando un conjunto de datos completo de declaraciones etiquetadas con diversos estados de salud mental. El objetivo es comprender y modelar el sentimiento asociado a diferentes estados de salud mental a partir de las declaraciones recopiladas.

## Conjunto de Datos

El conjunto de datos utilizado en este proyecto es una colección meticulosamente seleccionada de estados de salud mental etiquetados a partir de varias declaraciones. El conjunto de datos amalgama datos sin procesar de múltiples fuentes, los cuales han sido limpiados y compilados.

- **Fuente**: [Kaggle - Sentiment Analysis for Mental Health](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health?resource=download)

### Estados de Salud Mental Etiquetados

El conjunto de datos consta de declaraciones etiquetadas con uno de los siguientes siete estados de salud mental:

- Normal
- Depression
- Suicidal
- Anxiety
- Stress
- Bi-Polar
- Personality Disorder

## Contenido del Notebook

El notebook se compone de las siguientes partes:

1. **Análisis y Limpieza de Datos**: 
   - Se borran filas con valores nulos y columnas innecesarias.
   
2. **Estadísticas de los Estados de Salud Mental y sus Declaraciones**:
   - Análisis de la distribución de declaraciones por estado de salud mental.

3. **Análisis de Frecuencia de Palabras**:
   - Identificación de las palabras más frecuentes para cada estado de salud mental, incluyendo bigramas y trigramas.

4. **Análisis de Sentimientos**:
   - Realización de un análisis de sentimientos para cada estado de salud mental.

5. **Procesamiento de Texto**:
   - Lematización, tokenización y vectorización de las declaraciones para preparar los datos para los modelos de aprendizaje profundo y aprendizaje automático.

6. **Modelos de Clasificación**:
   - **Regresión Logística**: Implementación de un modelo de regresión logística para predecir si la declaración es de una persona sana o alguien con un problema mental.
   - **Redes Neuronales**: Implementación de un modelo de redes neuronales para compararlo con la regresión logística.
   - **Predicción Específica**: Implementación de un modelo de redes neuronales para predecir específicamente el estado de salud mental.

## Instalación

Para ejecutar este proyecto, ver el archivo requirements.txt
