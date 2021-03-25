# tp_aprendizaje_profundo

Integrantes:
BASMADJIAN, Martín Osvaldo
FERNANDEZ, Maria Emilia
 
El repositorio contiene
- Una [notebook desarrollada en Google Colab](https://colab.research.google.com/drive/14TmnnhidXVtJ8tmeZa_jq-A17qTvlDbZ?usp=sharing) con el código correspondiente a dos modelos de redes neuronales desarrollados sobre el dataset del MeLiChallenge del año 2019 ( Modelo de perceptrón multicapa y Modelo de red convolucional).
- En el archivo [mlruns_linea_base_mlp.tar.gz ](https://github.com/martinbas/tp_aprendizaje_profundo/blob/main/mlruns_linea_base_mlp.tar.gz) se encuentran las métricas de la clasificación a través de multilayer perceptron con los hiperparámetros de base obtenidos de la notebook original.
- En el archivo [mlruns_random_search_mlp.tar.gz](https://github.com/martinbas/tp_aprendizaje_profundo/blob/main/mlruns_random_search_mlp.tar.gz) se encuentran las métricas de la búsqueda aleatoria de hiperparámetros para la clasificación a través de multilayer perceptron.
- En el archivo [mlruns_experimento_mlp.tar.gz](https://github.com/martinbas/tp_aprendizaje_profundo/blob/main/mlruns_experimento_mlp.tar.gz) se encuentran las métricas de la clasificación a través de multilayer perceptron con los hiperparámetros obtenidos en la búsqueda aleatoria.
 
En ambos experimentos se exploraron hiperparámetros y la métrica de evaluación elegida fue balanced accuracy y observamos:
1. Siempre obtuvimos valores muy bajos de la métrica balanced accuracy (alrededor de 0.05).
2. Sin embargo, cuando incrementó la métrica balanced accuracy, disminuye la función de pérdida tanto de train como de validation.
