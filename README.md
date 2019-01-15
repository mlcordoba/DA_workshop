DATA ANALYTICS
=====================

Launch it with 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlcordoba/curso_DA/master)



## 1 - WORK ENVIRONMENT
The objective is to create the work environment, from the 'physical' desktop (Jupyter notebook), through the language (Python) and introducing the main tools for the analysis and visualization of the data (Numpy, Pandas and Matplotlib)

### 1.1 Jupyter Notebook
The notebooks involve the fusion of text editor, programming tool and visualization support, all accessible through the browser. They are currently, de facto, the way by which code is exchanged and results are displayed.

### 1.2 Basic elements of Python
Python is a programming language with a wider use than R, especially for Big Data application. Will be taught how to use basic elements of Python, such as data types (list, arrays, dictionaries), control flows (for loop, if / else), Input / Output data files and how to generate visualizations.

### 1.3 Numpy, Pandas and Matplotlib
These libraries are the main tools for the analysis and visualization of data. In this section we will go deeper than in section 1.2.


## 2 - DATA EXPLORATION - TIME SERIES
This second block will serve to put into practice as soon as possible what has been learned in block 1 and move on to manage data exploration techniques in a type of data that is very recurrent in the wind / energy sector.

### 2.1 Analysis of electricity demand in Spain
This type of time series is a good example to practice data management.

### 2.2 Temperature climatology in Spain
A good case to practice accessing databases on the web using APIs. It will also serve to exercise how to extract from large datasets usefull parameters and how to merge them with the energy demand series and analyze their impact.


## 3 - INSIGHTS INTO DATA INPUT
On numerous occasions the original data set is not able of leading to the best prediction model. To find the best model it is necessary to apply data cleansing techniques, for example, to select those variables that offer greater predictive power, create new variables using others as a starting point to improve the originals or simply eliminate those variables that degrade the system.

### 3.1 Factor analysis / ANOVA
Two of the most used techniques are presented to extract information on a set of variables and to be able to arrange them according to the impact they have on the dependent variable.

### 3.2 Clustering
The most used techniques are presented (among which K-means stands out) to separate data and categorize them.

### 3.3 Dimension reduction
The most used techniques are presented (among which the PCA stands out) in order to be able to construct a set of data of reduced dimensions, and therefore manageable, of better characteristics.

### 3.4 Feature Engineering
Analysis of different practical cases in which the construction of new variables produced an improvement in the prediction.


## 4 - TÉCNICAS REGRESIÓN Y CLASIFICACIÓN LINEAL
Se trata del primer bloque dedicado a la predicción. Se empezará a practicar con las dos ramas, regresión y clasificación. La regresión constituye una predicción de una variable continua, mientras que la clasificación trata de predecir una variables discreta.

#### 4.1 Regresión
Puesta en práctica de este tipo de predicción en problemas multidimensionales en Python.

#### 4.2 Clasificación
Puesta en práctica de este tipo de predicción mediante el uso de diferentes técnicas, entre las que destacan : Regresión logística, SVM o Perceptron.

#### 4.3 Árboles de decisión / Random Forest
Se trata de una técnica de predicción muy popular, fácil de implementar y a menudo suficiente. La pondremos en práctica para entre otros ejemplos, para predecir la generación eólica de un cartera de parques eólicos.



## 5 - TÉCNICAS REGRESIÓN Y CLASIFICACIÓN NO LINEAL
En este apartado se presentaran los elementos básicos de regresión y clasificación mediante redes neuronales. Además presentaremos, y usaremos, los frameworks más populares en Python (PyTorch, Keras y TensorFlow), algunos de ellos concebidos para el Deep Learning.

#### 5.1 Redes Neuronales Artificiales
Conceptos esenciales de Redes Neuronales Artificiales.

#### 5.2 Regresión
Puesta en práctica de este tipo de predicción en problemas multidimensionales.

#### 5.3 Clasificación
Puesta en práctica de este tipo de predicción.



## 6 - TÉCNICAS PREDICCIÓN PROBABILISTICA
Se presentaran los conceptos en este tipo de predicción. La diferencia principal es que el resultado final en lugar de ser un único valor determinista, es una distribución de probabilidad. Este tipo de predicción se adapta mejor a aquellos sistemas en los que existe algún tipo de incertidumbre, ya sea en las condiciones iniciales o en alguna parte de la dinámica procesos. Se presentará el framework PyMC3 diseñado para este tipo de predicción.

#### 6.1 Teorema de Bayes
Se trata de una parte fundamental de la predicción probabilística. Introduce los términos de distribución de probabilidad previa, posterior y probabilidad condicional. 

#### 6.2 Simulación de MonteCarlo
Se trata de una técnica para resolver problemas cuya solución es no analítica mediante el uso de elementos probabilísticos.

#### 6.3 Procesos estocasticos
Se presentan los tipos de procesos estocásticos y sus propiedades.

#### 6.4 Cadenas de Markov
Se trata de un tipo de proceso estocástico muy común cuyo estado futuro depende únicamente del estado presente. 

#### 6.5 MCMC
Parte fundamental de este bloque, donde se presenta los elementos prácticos de la predicción probabilística mediante procesos de cadenas de Markov, MC (Markov Chain) unido a simulación de Monte Carlo, MC.



## 7 - TÉCNICAS PREDICCIÓN DE SERIES TEMPORALES
La predicción de series temporales se puede abordar desde diferentes enfoques, ya sea mediante métodos lineales, como pueden ser los ARIMA o GARCH, mediante redes neuronales. En este apartado servirá pues como colofón a la parte de análisis de datos y técnicas de predicción.

#### 7.1 ARIMA / GARCH / Exponential Smoothing
Puesta en práctica de las clásicas técnicas de predicción de series temporales en Python.

#### 7.2 Redes Neuronales Artificiales
Emplearemos este tipo de técnica para resolver los aspectos no lineales en las series temporales.

#### 7.3 Filtro de Kalman
Técnica para ir corrigiendo iterativamente la predicción en función de la incertidumbre (errores previos) y las observaciones más recientes.



## 8 - BIG DATA EN LA NUBE
En este apartado se mostrarán los pasos a seguir para implantar un ecosistema de Big Data en una plataforma en la nube

#### 8.1 Plataformas en la nube AWS/GCP
Se presentarán la plataforma mas popular (AWS) y la que parece dispuesta a arrebatarle esa posición, GCP.

#### 8.2 Bases de datos
Un elemento fundamental en el diseño de un ecosistema de Big Data es la elección de la o las bases de datos. Estas deben encajar a la perfección con el tamaño presente y futuro de los datos y además del tipo de uso, intensivo/extensivo, que se haga de los datos almacenados.

#### 8.3 Computación
El segundo elemento fundamental en el diseño de un ecosistema de Big Data en la nube es la elección de los recursos de computación. Estos deben de encajar, sin idealmente estar sobre o infradimensionados. En este apartado analizaremos diferentes casos prácticos y su solución óptima.

#### 8.4 Pipelines
El tercer elemento fundamental. Adaptación de Python a ficheros de grandes dimensiones.

#### 8.5 Queries
El este apartado se hará uso del lenguaje SQL para poder hacer consultas a bases de datos masivas.

#### 8.6 Monitoring
El este apartado se presentan los diferentes elementos que se deben vigilar para que el sistema. Se aprovechará para enseñar elementos básicos de Linux, como utilizar la linea de comandos y algo de bash scripting.
