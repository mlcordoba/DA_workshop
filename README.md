DATA ANALYTICS
=====================

Launch it with 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlcordoba/curso_DA/master)



## 1 - WORK ENVIRONMENT
The objective is to create the work environment, from the 'physical' desktop (Jupyter notebook), through the language (Python) and introducing the main tools for the analysis and visualization of the data (Numpy, Pandas and Matplotlib)

### 1.1 Jupyter Notebook
The notebooks involve the fusion of text editor, programming tool and visualization support, all accessible through the browser. They are currently, de facto, the way by which code is exchanged and results are displayed.

### 1.2 Basic elements of Python
Python is a programming language with a wider use than R, especially for Big Data application. Will be taught how to use basic elements of Python, such as data types (list, arrays, dictionaries), control flows (for loop, if / else try / except), Input / Output data files and how to generate visualizations.

### 1.3 Numpy, Matplotlib and Pandas 
These libraries are the main tools for the analysis and visualization of data. In this section we will go deeper than in section 1.2.

### 1.4 Geeting data 
Very often data needs to be gather from different sources. Here we will get data using client APIs and also we will do some web scrapping if sources are a bit trickier.


## 2 - DATA EXPLORATION - TIME SERIES
This second block will serve to put into practice as soon as possible what has been learned in block 1 and move on to manage data exploration techniques in a type of data that is very recurrent in the wind / energy sector.

### 2.1 Analysis of electricity demand in Spain
This type of time series is a good example to practice data management.

### 2.2 Temperature climatology in Spain
A good case to practice accessing databases on the web using APIs. It will also serve to exercise how to extract from large datasets usefull parameters and how to merge them with the energy demand series and analyze their impact.


## 3 - INSIGHTS INTO DATA INPUT
Very often the original data set is not able to lead to the best prediction model. IIn order to acheive a better prediction it is necessary to apply data cleansing techniques, for example, to select those variables that offer greater predictive power, create new variables using others as a starting point to improve the originals or simply eliminate those variables that degrade the system.

### 3.1 Factor analysis / ANOVA
These two very popular techniques are introduce in here. They are used to extract information on a set of variables and sort them according to the impact they have on the dependent variable.

### 3.2 Clustering
Clustering techniques are used to separate data and categorize them. We will introduce the most popular ones with special empahsys on K-means.

### 3.3 Dimension reduction
Dimension reduction techniques are used to generate a smaller and manageable dataset while keeping its most importante characteristics.

### 3.4 Feature Engineering
Analysis of different practical cases in which the construction of new variables produced an improvement in the prediction.


## 4 - LINEAR REGRESSION AND CLASSIFICATION TECHNIQUES
This is the first block dedicated purely to prediction techniques. We will start working with the two branches of this field, regression and classification. The regression is a a continuous variable prediction problem, whereas classification tries to predict a discrete variable.

#### 4.1 Regression
We will work with this kind of prediction technique in a multidimensional system in Python.

#### 4.2 Classification
We will work with this kind of prediction technique using different techniques such as Logistic Regression, SVM or Perceptron.

#### 4.3 Decision trees / Random Forest
This is a very popular prediction technique, easy to implement and very often enough. We will put it into practice, by predicting the wind generation of a wind farm portfolio.



## 5 - NON-LINEAR REGRESSION AND CLASSIFICATION TECHNIQUES
This block will introduce the basic elements of non-linear regression and classification using artificial neural networks. We will also introduce and use, the most popular frameworks in Python (PyTorch, Keras and TensorFlow), some of them designed for specifically for Deep Learning.

#### 5.1 Artificial neural networks
Essential concepts of artificial neural networks.

#### 5.2 Regression
We will work with this kind of prediction technique in a multidimensional system in Python.

#### 5.3 Classification
We will work with this kind of prediction technique in a multidimensional system in Python.



## 6 - PROBABILISTIC PREDICTION TECHNIQUES
This block will introduce the basic concepts of this kind of prediction. The main difference is that the final result, instead of being a single deterministic value, it is a probability distribution. This kind of prediction is best suited for those systems in which there is some sort of uncertainty, either in the initial conditions or in some part of the dynamic proces. The PyMC3 framework for Python, designed specifically for this kind of prediction will be introduced.

#### 6.1 Bayes Theorem
It is a fundamental part of probabilistic prediction. We will deabte about the terms of likehood and previous, posterior and conditional probability distribution.

#### 6.2 MonteCarlo simulation
This is a technique using to solve probabilistic elements, problems with a non-analytical solution.

#### 6.3 Stochastic processes
Stochastic processes and their properties are introduced in here.

#### 6.4 Markov Chains
It is a very common type of stochastic process which future state depends solely on the present state.

#### 6.5 MCMC
A fundamental part of this block introducing the practical elements of probabilistic prediction through Markov chain processes, MC (Markov Chain) coupled with Monte Carlo simulation, MC.



## 7 - TIME SERIES FORECAST
Time series forecast cab be acheived through different approaches, either through linear methods, such as ARIMA or GARCH or through artificail neural networks. This block will recap all techniques to solve this important kind of prediction problem.

#### 7.1 ARIMA / GARCH / Exponential Smoothing
Implementation of the classic techniques of prediction of time series in Python.

#### 7.2 Artificial Neural Networks
We will use this kind of technique to solve non-linear aspects in time series.

#### 7.3 Kalman filter
Technique to iteratively correct the prediction based on the uncertainty (previous errors) and the most recent observations.



## 8 - BIG DATA IN THE CLOUD
This block will show the steps to follow to implement a Big Data environment in a typical cloud platform

#### 8.1 AWS / GCP cloud platforms
The most popular platform (AWS) will be introduced along with the one that could eventually take its position, GCP.

#### 8.2 Databases
A key element in the design of a Big Data environemnt is the database(s) selection. The database has to fit perfectly with the current and future size of the data inflow, and also be able to cope with the analysis underatook on the stored data by the end-users.

#### 8.3 Computing
The second key element in the design of a Big Data environemnt in the cloud is the computing resources selection. The compute has not to be at any time oversized nor undersized. We will analyze different practical cases and their optimal solution.

#### 8.4 Pipelines : ETL
The third key element. Extraction, Transform and Load of large files of data using Python.

#### 8.5 Queries
In this section we will use the SQL language to query massive databases.

#### 8.6 Monitoring
This section introduce the different systems elements that has to be monitored for the sake of its health. We will also introduce basic Linux elements, such as using the command line and some bash scripting techniques.
