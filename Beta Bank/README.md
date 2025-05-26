# 🏦 Predicción de Fuga de Clientes - Beta Bank

## 📌 Descripción del Proyecto

Beta Bank está enfrentando un problema creciente: cada mes, algunos de sus clientes cancelan sus contratos y abandonan el banco. Se ha determinado que es más económico retener a los clientes existentes que adquirir nuevos, por lo que el banco busca una solución basada en datos para identificar a los clientes con mayor probabilidad de cancelar su contrato próximamente.

Tu tarea como analista de datos es desarrollar un modelo de clasificación que prediga con la mayor precisión posible si un cliente está en riesgo de dejar el banco.

## 🎯 Objetivo

- Construir un modelo de clasificación binaria para predecir la fuga de clientes.
- Maximizar la métrica **F1-Score** (mínimo requerido: **0.59**).
- Medir y comparar la métrica **AUC-ROC** con F1 para evaluar la calidad general del modelo.

## 📦 Librerías utilizadas

Este proyecto se desarrolla en Python y utiliza las siguientes librerías:

1. pandas | Manipulación de datos |
2. numpy | Cálculo numérico eficiente |
3. matplotlib.pyplot | Gráficos básicos visuales |
4. seaborn | Visualización estadística avanzada |
5. train_test_split | División de datos |
6. GridSearchCV | Optimización de hiperparámetros |
7. RandomForestClassifier | Clasificación con árboles |
8. DecisionTreeClassifier | Árboles de decisión |
9. LogisticRegression | Clasificación lineal binaria |
10. accuracy_score | Evaluación de modelos |
11. StandardScaler | Normalización de variables |
12. SimpleImputer | Imputación de valores |
13. shuffle | Aleatorización de datos |

## 🧠 Instrucciones para ejecutar

1. Clonar este repositorio.
2. Instalar las dependencias con:

   pip install -r requirements.txt
