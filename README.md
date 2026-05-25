# TFG Implementaciones en Python | [Universidad de Sevilla] | [2026]
Este repositorio contiene las implementaciones desarrolladas como parte de mi TFG. Incluye algoritmos clásicos de aprendizaje automático aplicados al dataset Iris, redes neuronales recurrentes aplicadas a MNIST, y el núcleo del trabajo: una comparativa entre modelos de regresión clásicos y arquitecturas LSTM/GRU para la predicción de series temporales financieras (S&P 500).
## Estructura del repositorio
ANN básicas

  └─ basicrnn.ipynb
  
  └─ mnist_rnn.ipynb
  
  └─ mnistANN.ipynb
  
Machine learning iris

  └─ decisiontreeIris.ipynb
  
  └─ irisclassifier.ipynb
  
  └─ iris_reg_logistica.ipynb
  
  └─ knniris.ipynb
  
  └─ svmiris.ipynb

Otras visualizaciones

  └─ tipos_aprendizaje.ipynb
  
  └─ unrolled_rnn.ipynb
  

  
Predicción sp500

  └─ comparacion1_reglineal.ipynb
  
  └─ comparacion2_reglog.ipynb    

## Contenido
### Generación de gráficos y esquemas
Tanto en la carpeta de Otras visualizaciones como en el resto de archivos se incluyen gráficas y esquemas representativos de los distintos modelos de Machine Learning.

### Clasificación sobre el dataset Iris
Implementaciones con scikit-learn de algunos de los algoritmos más representativos del ML:

- Árbol de decisión
- Perceptrón — separador lineal binario
- Regresión logística — clasificación probabilística binaria
- K-Nearest Neighbors (KNN) — clasificación por proximidad
- Support Vector Machine (SVM) — hiperplano de máximo margen

### Redes neuronales sobre MNIST

- RNN básica — introducción a las redes recurrentes aplicada al reconocimiento de dígitos.
- ANN general — red feedforward totalmente conectada para clasificación de imágenes.

### Predicción del S&P 500
Comparativa entre modelos clásicos y arquitecturas recurrentes profundas para la predicción de series temporales financieras:

- Regresión lineal vs. LSTM vs GRU: predicción del precio de cierre del SP500 en función del cierre de los últimos 30 días.
- Regresión logística vs. LSTM vs. GRU: predicción del régimen de volatilidad del mercado del SP500. 


