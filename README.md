# Clasificaci-n-de-prendas-de-ropa-con-TensorFlow-y-Keras

Este proyecto implementa un clasificador de prendas de ropa usando la base de datos Fashion MNIST, con TensorFlow y Keras. El modelo aprende a identificar diferentes categorias de ropa a partir de imagenes en escala de grises.

Tecnologías utilizadas:
Python 3.x
TensorFlow 2.x
Keras
NumPy
Matplotlib

Carga y exploración del dataset:

Se carga la dataset Fashion MNIST, que contiene 70,000 imágenes de 28x28 píxeles categorizadas en 10 clases de prendas de ropa.
Se visualizan algunas imágenes para entender su contenido.


![image](https://github.com/user-attachments/assets/b635b249-75e4-44cd-9255-f1dc237b814b)



Preprocesamiento:

Las imágenes se normalizan dividiéndolas por 255 para que los valores estén en el rango [0, 1].}

![image](https://github.com/user-attachments/assets/96678bb5-941a-4a24-b483-926f50b8d14e)



Construcción y entrenamiento del modelo:

Se crea un modelo secuencial con una capaFlatten, una capa Dense oculta de 128 neuronas con activación ReLU y una capa de salida con 10 neuronas y activación softmax.
Se compila el modelo usando el optimizador Adam y la pérdida de entropía cruzada categórica.
Se entrena por 10 épocas con los datos de entrenamiento.

![image](https://github.com/user-attachments/assets/1bdd760a-168d-4c27-b743-a564ed85c6c9)



Evaluación y predicciones:

Se evalúa el modelo con los datos de prueba.
Se generan predicciones para las imágenes de prueba.
Se visualizan algunas predicciones junto con las imágenes originales, destacando las predicciones correctas en azul y las incorrectas en rojo.


![image](https://github.com/user-attachments/assets/f3281648-1866-4e8a-95a4-48896b985a9e)


Visualización de resultados:

Se muestran varias imágenes de prueba con sus predicciones y probabilidades.
Se analiza una predicción individual sobre una imagen específica.
