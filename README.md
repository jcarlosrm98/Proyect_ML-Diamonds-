# Proyect ML Diamonds
En este repositorio encontrarás varios datasets con diversas características sobre diamantes. En este proyecto, se ha creado una competición en Kaggle para generar un modelo predictivo para lograr predecir el precio de unos diamantes. 
El repositorio contiene dos notebooks, uno para entrenar el modelo y otro para realizarle el test.

## Status
Ironhack Data Analytics Project. Beta version.

## Technology stack

Este proyecto ha sido generado en Python:
Librerías utilizadas en Python:

1. "Pandas" para obtener y devolver DataFrames.
2. "sk-learn" para realizar el preprocessing y entrenar modelos.
3. "XGBOOST" como modelo utilizado.

## Use and operation

En el primer notebook (denominado Train) encontrarás el código para realizar el preprocessing del modelo y su entrenamiento.
En el segundo notebook (denominado Test) encontrarás el código para poder testear los resultados del entrenamiento
Además también se encuentra la carpeta "Models" y "Submissions" donde encontrarás los modelos guardados, así como los modelos que se subieron a las competición.

La competición fue realizada en: https://www.kaggle.com/competitions/ih-datamadpt-0124-project-m-3

## Architecture

1. Los dataframes estaban en .db y fueron utilizados desde SQLAlchemy.
2. El preprocessing fue realizado utilizando Sklearn.
3. El modelo elegido fue XGBOOST.
