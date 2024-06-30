# Proyecto_Statistical_Learning_1
Proyecto del curso Statistical Learning 1 

# Proyecto de Clasificación de Modelos

Este proyecto tiene como objetivo desarrollar y evaluar varios algoritmos de clasificación para determinar el rendimiento de cada uno en la predicción de la posición de jugadores de fútbol basada en sus estadísticas.

## Contenido

- [Descripción](#descripción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Modelos y Hiperparámetros](#modelos-y-hiperparámetros)
- [Resultados](#resultados)
- [Autores](#autores)

## Descripción

En este proyecto, se desarrollan y analizan los siguientes algoritmos de clasificación:

- Naive Bayes
- LDA (Análisis de Discriminante Lineal)
- Regresión Logística
- SVM (Máquinas de Vectores de Soporte)
- Árboles de Decisión
- Random Forest
- QDA (Análisis de Discriminante Cuadrático)
- AdaBoost
- Gradient Boosting
- XGBoost
- LGBM (LightGBM)

Para cada algoritmo, se entrenan y evalúan al menos cinco configuraciones de hiperparámetros diferentes.

## Instalación

Para ejecutar este proyecto, necesitarás tener instalado Python y las siguientes bibliotecas:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm
```
## Uso

1. Clonar este repositorio:
```
git clone https://github.com/marinhoGC/Proyecto_Statistical_Learning_1.git 
```
2. Navegar al directorio del proyecto:
```
cd Proyecto_Statistical_Learning_1
```
3. Ejecutar los notebooks para entrenar y evaluar los modelos.


## Modelos y Hiperparámetros

Los siguientes modelos se entrenaron y evaluaron con varias configuraciones de hiperparámetros:

- Naive Bayes: (GaussianNB)
- LDA: (LinearDiscriminantAnalysis)
- Regresión Logística: (LogisticRegression)
- SVM: (SVC)
- Árboles de Decisión: (DecisionTreeClassifier)
- Random Forest: (RandomForestClassifier)
- QDA: (QuadraticDiscriminantAnalysis)
- AdaBoost: (AdaBoostClassifier)
- Gradient Boosting: (GradientBoostingClassifier)
- XGBoost: (XGBClassifier)
- LGBM: (LGBMClassifier)

## Resultados

Se evaluaron los modelos utilizando un conjunto de entrenamiento y prueba. Los resultados incluyen precisión, F1-score, tiempo de entrenamiento y la fecha y hora de finalización del entrenamiento. L

## Autores

Jorge Mario García - Desarrollador Principal - MarinhoGC

