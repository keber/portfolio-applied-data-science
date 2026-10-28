# Ciencia de datos aplicada: selección de trabajos del diplomado

Este repositorio reúne una selección de ejercicios y secciones de capstones que desarrollé durante el Diplomado en Ciencia de Datos UDD. Está orientado a mostrar análisis, preparación de datos, comparación de modelos y decisiones basadas en sus errores. Los proyectos de adquisición y procesamiento de datos están en el [portafolio de ingeniería de datos](https://github.com/keber/portfolio-data-engineering).

Los notebooks del diplomado fueron entregas grupales con responsables distintos por tema. La selección y la atribución se basan en `Planificación Grupal.xlsx`. Los cuadernos de esta carpeta son **extractos curados**, sin salidas ni datos; conservan código de los segmentos asignados a Keber/KFB y no se presentan como demostraciones reproducibles autónomas.

El capstone de perros y gatos se desarrolló en conjunto por el equipo. Su ficha se atribuye al grupo y examina los resultados guardados en el notebook original; aún no se ha extraído código de ese trabajo a esta carpeta.

## Casos seleccionados

| Caso | Pregunta y aporte | Estado de la selección |
| --- | --- | --- |
| [Detección de fraude con tarjetas](casos/fraude-tarjetas.md) | Comparar clasificadores ante una clase minoritaria y discutir falsos positivos frente a fraudes no detectados. | Sección de tarjetas del capstone supervisado, asignada a KFB. |
| [Categorías de precio de departamentos](casos/precios-departamentos.md) | Comparar selección de variables y PCA para predecir una categoría de precio. | Actividades 2 y 3 del capstone no supervisado, asignadas a KFB. |
| [Pronóstico de PM2.5](casos/pm25.md) | Explorar cambios de arquitectura y variables en una red convolucional 1D para series temporales. | Bitácora DL12 asignada a Keber. |
| [Perros y gatos con transfer learning](casos/perros-gatos-transfer-learning.md) | Adaptar InceptionV3 y comparar el clasificador inicial con el ajuste fino mediante matrices de confusión. | Capstone grupal del módulo 7; ficha de análisis, sin notebook curado todavía. |
| [Selección de variables](casos/seleccion-variables.md) | Analizar redundancia y comparar métodos de selección para clasificadores. | Bitácora UL05 asignada a Keber; extracto curado con advertencia de fuga de información en una actividad. |
| [Pruebas A/B](casos/pruebas-ab.md) | Examinar cómo cambian la conversión y la incertidumbre según las decisiones de análisis. | Bitácora IE12_2 asignada a Keber; extracto curado, con datos originales ausentes. |

Las [piezas complementarias](casos/piezas-complementarias.md) reúnen inferencia con encuestas sintéticas, un experimento de entrenamiento en PyTorch, curvas de evaluación y una regresión logística implementada manualmente. Refuerzan los casos principales sin presentarse como proyectos completos.

Los extractos de código están en [`notebooks/`](notebooks/). Requieren celdas previas de preparación, dependencias y datos del curso que no se incluyen aquí. El objetivo de esta versión es mostrar el razonamiento y las partes implementadas, con límites claros. No se copiaron los cuadernos completos del grupo.

## Otros ejercicios propios que podrían curarse después

La planificación también me asigna bitácoras de preparación de datos y otros ejercicios introductorios. Los que tienen una historia técnica clara aparecen arriba; el resto queda como material de aprendizaje. Recuperé mi versión del ejercicio de DataFrames (`BD02-DataFrames_OLD.ipynb`) y seleccioné parte de ese código para el portafolio de ingeniería de datos.

## Procedencia

La planilla de coordinación y los datos originales permanecen fuera de esta carpeta. Los capstones se atribuyen por sección; las consignas, el resto de las soluciones y la reflexión grupal no se han incorporado. Este repositorio aún no tiene una revisión de ejecución independiente de los extractos.
