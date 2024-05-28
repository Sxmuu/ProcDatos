# Proyecto Procesamiento de Datos a Gran Escala

Este repositorio contiene toda la información relacionada con la entrega final del proyecto de Procesamiento de Datos a Gran Escala, desarrollado para la materia Procesamiento de Datos 2024 bajo la supervisión del Dr. John Corredor.

## Objetivos del Proyecto

- Comprender la importancia del uso de herramientas de Big Data en entornos empresariales para solucionar preguntas de negocio.
- Realizar procesamiento de datos con Apache Spark y Databricks aplicado a un problema real.
- Seguir la metodología CRISP-DM para generar hallazgos de valor a partir del procesamiento de datos.

## Estructura del Proyecto

El proyecto se dividió en dos entregas principales, siguiendo la metodología CRISP-DM, utilizando herramientas de Big Data como Databricks y Apache Spark.

### Entrega 1: Entendimiento del Negocio y Entendimiento de los Datos

1. **Entendimiento del Negocio**: Se presentó un contexto general de la situación en Nueva York, incluyendo indicadores macroeconómicos relevantes y el objetivo del equipo de consultoría.
2. **Selección de los Datos**: Se listaron los conjuntos de datos utilizados, justificando su selección basada en el objetivo de negocio. Los datos incluían:
   - Datos de arrestos en Nueva York
3. **Colección y Descripción de Datos**: Se cargaron los datos en Databricks y se describieron según tipos de datos, significado de cada atributo y una descripción general del contenido.
4. **Exploración de los Datos**: Se presentaron estadísticos descriptivos, gráficas y tablas agregadas para facilitar el entendimiento de la estructura y comportamiento de los datos.
5. **Reporte de Calidad de Datos**: Se realizó el conteo de valores faltantes y se propusieron técnicas para tratarlos.
6. **Planteamiento de Preguntas sobre los Datos**: Se establecieron preguntas de negocio relacionadas con los datos a responder en la segunda entrega.
7. **Filtros, Limpieza y Transformación Inicial**: Se presentaron algunas transformaciones y filtros iniciales sobre los datos.

#### Bono

- Se realizó un proceso de web scraping para extraer información poblacional y se generaron gráficos.
- Se extrajo información climática de una API y se generaron gráficos.

### Entrega 2: Preparación de Datos, Modelado y Presentación de Resultados

1. **Filtros y Transformaciones Finales**: Se presentaron las transformaciones finales y filtros aplicados sobre los datos, justificando estos procedimientos.
2. **Respuesta a Preguntas de Negocio**: Se presentaron tablas y visuales que respondían las preguntas de negocio planteadas en la primera entrega.
3. **Selección de Técnicas de Aprendizaje de Máquina**: Se seleccionó una técnica de aprendizaje supervisado y una no supervisado, justificando su elección en función del objetivo de negocio.
4. **Preparación de Datos para Modelado**:
   - Eliminación de características fuertemente correlacionadas.
   - Normalización de variables numéricas.
   - Selección de variables según criterio de negocio.
5. **Aplicación de Técnicas de Aprendizaje de Máquina**: Se aplicaron las técnicas seleccionadas utilizando Mlib en Databricks.
6. **Evaluación de Modelos**: Se aplicaron métricas adecuadas al problema y se realizaron pruebas con diferentes parámetros para cada técnica.

#### Bono

- Se construyó un modelo de aprendizaje profundo utilizando redes neuronales.

## Repositorio

El repositorio contiene los siguientes archivos:

- **Documento de la Entrega Final**: Detalla todos los pasos y resultados del proyecto.
- **Cuadernos de Trabajo**: Documentados y membreteados, utilizados en Databricks para el procesamiento de datos.
- **Código Fuente**: Scripts de procesamiento y modelado de datos.

## Herramientas Utilizadas

- Apache Spark
- Databricks
- Herramientas de Web Scraping
- API de OpenWeatherMap
