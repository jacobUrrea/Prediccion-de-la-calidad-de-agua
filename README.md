# Prediccion-de-la-calidad-de-agua

***Pontificia Universidad Javeriana***
# **Procesamiento de Alto Volumen de Datos**

### Taller: **Tratamiento de Datos y Machine Learning con PySpark**

Autor: Andres Jacobo Urrea
 
Fecha de Inicio: 16/04/2026 

Fecha actual: 23/04/2026

## **Problemática**

Se tiene que el tratamiento del agua debe ser indispensable para garantizar la pureza y la calidad. Uno de los elementos significativos es aplicar los conceptos de los Procesamientos de Datos en Alto Volúmen para solucionar este tipo de problemas que afectan la salud publica. El presente ejemplo tiene como propósito tener en cuenta una metodogología para aplicar el PAVD para solucionar o diagnósticar la calidad del agua en la INDIA.

## **Objetivo**

Implementar modelos de predicción utilizando la biblioteca de aprendizaje automático MLlib PySpark, con el fin de explorar y aplicar técnicas de IA en entornos de procesamiento con alto volúmen de datos.

## **Tecnologías Utilizadas**

- **Apache Spark / PySpark** — Procesamiento distribuido y consultas SQL
- **Pandas y NumPy** — Manipulación y transformación de datos en memoria
- **Matplotlib y Seaborn** — Visualización estadística y gráficas exploratorias
- **GeoPandas** — Análisis geoespacial y mapas coropléticos
- **Scikit-Learn** — División de datos en entrenamiento y prueba
- **TensorFlow y Keras** — Construcción y entrenamiento de la red neuronal

## **Metodología**

1.- Importación de los datos (datos en diferentes formatos)

2.- Preprocesamiento y limpieza de valores nulos, cambio de datos, EDA, medidas estadísticas.

3.- Entrenamiento de modelos: RL (MLlib), tensores (KERAS); la idea es predecir la calidad del agua en la INDIA.

4.- Evaluación de los modelos: medidas de rendimiento tales como: precisión (precision), exactitud (accuracy), recall, F1 Score,entre otras.

5.- Se tiene como referencia de la calidad de los parámetros del agua, la referencia: https://www.intechopen.com/chapters/69568

## **Resultados Clave**

- Se logró construir un índice de calidad del agua (WQI) representativo a partir de variables
- El análisis geográfico permitió identificar diferencias significativas en la calidad del agua entre los distintos estados de India
- El modelo de red neuronal demostró un desempeño satisfactorio en la predicción del WQI sobre el conjunto de prueba
- Se identificaron parámetros críticos como las bacterias coliformes fecales y el oxígeno disuelto como los de mayor impacto en la calidad del recurso hídrico
