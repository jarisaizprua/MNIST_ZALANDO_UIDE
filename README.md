# MNIST ZALANDO

## Grupo 4 - Integrantes
* EDGAR DANIEL SULCA NARANJO
* GABRIELA ESTEFANIA CHILIQUINGA JIMENEZ
* KAREN LISSETTE PLAZA JIMENEZ
* MARJURY LISBETH DIAZ HARO
* JARIS SURYA AIZPRUA BARRIOS

## 1) Contenido
* Cargar los datos de entrenamiento y prueba desde archivos CSV.
* Preparar y normalizar los datos para el modelo.
* Dividir el conjunto de datos de entrenamiento para incluir un conjunto de validación.
* Construir un modelo de red neuronal simple con TensorFlow y Keras.
* Entrenar el modelo con los datos de entrenamiento.
* Evaluar el rendimiento del modelo con el conjunto de datos de prueba.
* Visualizar algunas de las imágenes de entrenamiento.
* Crear y analizar las matrices de confusión de las predicciones.

## 2) Interpretación de las Matrices de Confusión

  Diagonal Principal: Los valores en la diagonal principal de cada matriz indican el número de predicciones correctas para cada clase. Cuanto más altos sean estos valores, mejor será el rendimiento del modelo para esa clase específica.

  Fuera de la Diagonal: Los valores fuera de la diagonal principal indican confusiones entre clases, es decir, cuántas veces el modelo predijo incorrectamente una clase por otra. Estos valores ayudan a identificar qué clases se confunden más frecuentemente entre sí.

  Comparación entre Conjuntos: Comparar las matrices de confusión del conjunto de entrenamiento y de prueba puede revelar si el modelo está sobreajustado. Si el modelo tiene un rendimiento significativamente mejor en el conjunto de entrenamiento que en el conjunto de prueba, esto puede indicar sobreajuste.

  Balance de Clases: Si observas que algunas clases tienen un número mucho mayor de predicciones incorrectas (tanto como falsos positivos como falsos negativos), esto podría indicar un desequilibrio de clases en el conjunto de datos o que el modelo tiene dificultades para aprender características distintivas de esas clases particulares.
