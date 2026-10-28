# Detección de fraude en transacciones con tarjeta

**Fuente de trabajo:** sección «Set de Datos Tarjetas de Créditos» de `06/CAPSTONE/SL15-CAPSTONE_PROJECT.ipynb`. La planificación grupal asigna ese conjunto de datos a KFB (`modulo 6!H16`). El notebook completo contiene además otros conjuntos trabajados por compañeros; esta selección empieza en la sección de tarjetas.

El conjunto de entrenamiento tenía una clase de fraude muy minoritaria. Separé entrenamiento y prueba antes de aplicar SMOTE al entrenamiento, y comparé regresión logística, Random Forest y Gradient Boosting mediante reportes de clasificación y matrices de confusión.

La conclusión del trabajo destaca una decisión práctica: los modelos que detectan más fraudes pueden generar muchas alertas falsas. Random Forest mostró menos falsos positivos en esa comparación, con más fraudes no detectados. Por eso la elección del modelo depende del costo operativo de revisar alertas y del costo de dejar pasar fraude; una sola métrica agregada sería insuficiente.

El [extracto de código](../notebooks/fraude_tarjetas_curado.ipynb) omite el dataset y las salidas guardadas. La fuente usa una ruta de Google Drive, reemplazada por una variable de entorno para esta versión. Los resultados numéricos no se recalcularon durante esta curaduría. Una celda de análisis del notebook original invierte las etiquetas de falsos positivos y falsos negativos para Gradient Boosting respecto de la conclusión; por eso no se publican esos conteos como resultados verificados.
