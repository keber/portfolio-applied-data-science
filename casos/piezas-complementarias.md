# Piezas complementarias de ciencia de datos

Estos extractos respaldan técnicas concretas del diplomado. Se mantienen separados de los casos principales porque son ejercicios acotados o porque sus resultados no permiten una conclusión aplicada amplia.

## Inferencia con encuestas sintéticas: LePac

Las actividades 3 y 4 del capstone `04/CAPSTONE/IE14_CAPSTONE_LePac_CIENCIA_DATOS.ipynb` están asignadas a KFB (`modulo 4!E15`). Keber formuló una prueba t frente a un umbral de satisfacción y comparó LePac con Capel y con un competidor. El notebook distingue un contraste con resultado significativo de otro para el cual no encontró evidencia suficiente. Las encuestas se **generaron para la consigna** con promedios objetivo; esto demuestra formulación e interpretación de hipótesis sobre datos sintéticos, no satisfacción observada de consumidores. [Código seleccionado](../notebooks/inferencia_lepac_curado.ipynb).

## Arquitectura y costo de entrenamiento en PyTorch

`07/DL04-Entrenamiento_Pytorch.ipynb` está asignado a Keber (`modulo 7!E6`). El experimento entrena seis tamaños de capa oculta sobre **MNIST** y registra pérdida de entrenamiento y duración. Es una buena pieza para explicar el costo de aumentar capacidad, pero no calcula una métrica de prueba comparable para las seis variantes; por eso no permite concluir cuál generaliza mejor. [Código seleccionado](../notebooks/pytorch_tamano_capa_curado.ipynb).

## Curvas de diagnóstico de clasificadores

`06/SL14-Curvas_de_analisis_modelos_clasificacion.ipynb` está asignado a Keber (`modulo 6!E15`). Con un clasificador de supervivencia en Titanic, la bitácora muestra matriz de confusión, curva Precision–Recall, ROC y ganancia acumulada. Sirve para explicar el tipo de diagnóstico que interesa en el [caso de fraude](fraude-tarjetas.md), pero las curvas guardadas corresponden a **Titanic**, no al dataset de transacciones. [Código seleccionado](../notebooks/curvas_clasificacion_curado.ipynb).

## Regresión logística implementada desde cero

La bitácora `06/SL05-Regresion_logistica.ipynb` está asignada a Keber (`modulo 6!E6`). En su actividad 2 implementó función sigmoidea, pérdida, gradiente y actualización de pesos, y comparó la predicción binaria de Iris con `scikit-learn`. La salida guardada reporta exactitud de 1,00 para ambas implementaciones en esa partición; es una comprobación didáctica, no una estimación de generalización. [Código seleccionado](../notebooks/regresion_logistica_manual_curado.ipynb).

Estas piezas no incorporan los cuadernos grupales completos ni sus datasets. Los extractos carecen de salidas y algunos dependen de celdas previas del material de curso; sus resultados no se recalcularon en esta curaduría.
