# Predicción de Variables en Máquinas Generadoras de Electricidad

Este repositorio contiene un notebook diseñado para ayudar a los operadores de equipos de generación de electricidad a predecir el comportamiento de variables específicas a partir de datos históricos. Utiliza técnicas de regresión multivariable para ajustar un modelo predictivo.

## Contenido del Notebook

1. **Importación de Bibliotecas**: Se importan las bibliotecas necesarias para la manipulación de datos, visualización y modelado.
2. **Carga de Datos**: Se carga el dataset desde un archivo CSV.
3. **Exploración de Datos**: Se exploran y visualizan las características del dataset.
4. **Preprocesamiento de Datos**: Se preparan los datos para el modelado, incluyendo la normalización y la división en conjuntos de entrenamiento y prueba.
5. **Entrenamiento del Modelo**: Se entrena un modelo de regresión lineal multivariable.
6. **Evaluación del Modelo**: Se evalúa el rendimiento del modelo utilizando métricas como el MSE y el R².
7. **Predicciones**: Se realizan predicciones con el modelo entrenado.

## Cómo Usar

1. Clona este repositorio: `git clone https://github.com/tu_usuario/tu_repositorio.git`
2. Navega al directorio del repositorio: `cd tu_repositorio`
3. Abre el notebook con Jupyter: `jupyter notebook notebook.ipynb`
4. Sigue las instrucciones en el notebook para cargar tu propio dataset y entrenar el modelo.

## Requisitos

- Python 3.x
- Bibliotecas: pandas, numpy, scikit-learn, matplotlib, seaborn, jupyter

## Instalación de Requisitos

Puedes instalar los requisitos con el siguiente comando:
```sh
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
