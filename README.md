## 🚧 Proyecto en Desarrollo 🚧
Este proyecto aún está en desarrollo y puede contener errores o funciones incompletas. 

# 🌐 Web Interactiva: Python, Machine Learning y CNN para Conteo de Personas

[![GitHub](https://img.shields.io/badge/GitHub-sergijmejia-181717?style=flat&logo=github)](https://github.com/sergijmejia/quartoWebsite)
[![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)](#)
[![Quarto](https://img.shields.io/badge/Quarto-website-lightgrey?style=flat&logo=quarto)](#)

Esta web educativa desarrollada con **Quarto** tiene dos objetivos principales:

1. Introducir conceptos de **Python**, **Machine Learning** y **Redes Neuronales**.
2. Presentar un **proyecto práctico de Head-count**, donde un modelo CNN es entrenado para **contar la cantidad exacta de personas en imágenes**.

---

## 🔹 Contenido de la Web

### 1️⃣ Python
- Conceptos básicos: variables, estructuras, funciones.
- Análisis de datos con: `numpy`, `pandas`, `matplotlib`, `seaborn`.
- ML y Deep Learning: `scikit-learn`, `tensorflow`.
- **Notebooks interactivos incluidos:**
  - [NumPy](python/numpy.ipynb)
  - [Pandas](python/pandas.ipynb)
  - [Matplotlib](python/matplotlib.ipynb)
  - [Seaborn](python/seaborn.ipynb)
  - [Scikit-learn](python/scikit-learn.ipynb)
  - [TensorFlow](python/tensorflow.ipynb)

### 2️⃣ Machine Learning
- Conceptos clave: datasets, entrenamiento, validación, métricas.
- Aprendizaje supervisado: regresión lineal, overfitting/underfitting, k-neighbors, árboles de decisión.
- **Notebooks incluidos:**
  - [Supervised Intro](machine_learning/supervised_intro.ipynb)
  - [Linear Regression](machine_learning/linear_regression.ipynb)
  - [Overfitting & Underfitting](machine_learning/overfitting_underfitting.ipynb)
  - [Train/Test Split](machine_learning/train_test.ipynb)
  - [K Neighbors](machine_learning/k_neighboors.ipynb)
  - [Tree Methods](machine_learning/tree_methods.ipynb)

### 3️⃣ Neural Networks
- Conceptos de redes neuronales y CNN.
- Tipos de redes: CNN, GAN, RNN, series temporales, NLP.
- **Notebooks incluidos:**
  - [CNN](neural_networks/cnn.ipynb)
  - [GAN](neural_networks/gan.ipynb)
  - [Time Series](neural_networks/ts.ipynb)
  - [RNN](neural_networks/rnn.ipynb)
  - [NLP](neural_networks/nlp.ipynb)

### 4️⃣ Google Colab
- Introducción al uso de Colab para experimentos interactivos.
- **Contenido:** [Colab Intro](colab/colab_intro.qmd)

### 5️⃣ Head-count Project
- Proyecto práctico de conteo de personas en imágenes con CNN.
- **Archivos incluidos:**
  - [Project Intro](project/Project_intro.qmd)
  - [HeadCounting Notebook](project/Proyecto_HeadCounting.ipynb)

### 6️⃣ About
- Información sobre el autor y la web:
  - [About Me](about/about_me.qmd)
  - [About Site](about/about_site.qmd)

---

## 🗂 Estructura del Proyecto
```
├── python/ # Contenido de Python y notebooks
├── machine_learning/ # Notebooks de ML
├── neural_networks/ # Notebooks de redes neuronales
├── colab/ # Introducción a Google Colab
├── project/ # Head-count project
├── about/ # Información sobre el sitio y autor
├── _quarto.yml # Configuración del sitio Quarto
├── styles.css # Estilos personalizados
└── README.md # Documentación del proyecto
```
  ---

## 🛠 Tecnologías Utilizadas
- **Quarto**: generación de la web interactiva.
- **Python 3.10+**: análisis de datos, ML y Deep Learning.
- **PyTorch / TensorFlow**: construcción de modelos CNN.
- **Jupyter Notebooks**: experimentos interactivos.
- **HTML/CSS**: personalización de la web.

---

## ⚡ Cómo ejecutar el proyecto

1. **Clonar el repositorio:**
```
git clone https://github.com/sergijmejia/quartoWebsite.git
cd quartoWebsite
```
2. **Instalar dependencias (Python y Quarto):**
```
pip install -r requirements.txt
quarto check install
```
3. **Renderizar la web:**
```
quarto render
```
4. **Abrir la web localmente:**
```
quarto preview
```
