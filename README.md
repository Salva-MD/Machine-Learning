# Machine-Learning
Este repositorio contiene cuatro proyectos enfocados en análisis de datos, modelado predictivo y evaluación de resultados en distintos ámbitos empresariales e industriales.

---

## Proyecto 1: Clasificación de Planes para Megaline

La compañía móvil **Megaline** quiere analizar el comportamiento de sus clientes para recomendar uno de los nuevos planes prepago: **Smart** o **Ultra**. Usando datos de clientes que ya han cambiado a estos planes, el objetivo es crear un modelo de clasificación con una precisión mínima de 0.75 para predecir el plan más adecuado para cada usuario.

---

## Proyecto 2: Predicción de Cancelación de Clientes para Beta Bank

Beta Bank enfrenta la pérdida gradual de clientes y busca predecir qué clientes están en riesgo de abandonar el banco. Utilizando datos históricos de comportamiento y terminación de contratos, se debe crear un modelo que maximice la métrica F1, con un umbral mínimo de 0.59 en el conjunto de prueba. Además, se evaluará y comparará la métrica AUC-ROC para complementar el análisis.

---

## Proyecto 3: Optimización de Ubicación de Pozos Petrolíferos para OilyGiant

La compañía petrolera **OilyGiant** busca abrir 200 nuevos pozos en la región más rentable. Los pasos incluyen:

- Leer datos de calidad de crudo y volumen de reservas de pozos en tres regiones.
- Crear un modelo de regresión lineal para predecir el volumen de reservas.
- Seleccionar los mejores pozos según estimaciones y calcular beneficios.
- Usar bootstrapping para evaluar riesgos y seleccionar la región con mayor beneficio esperado y un riesgo de pérdida inferior al 2.5%.

Condiciones clave: presupuesto limitado, precio por barril, y volumen expresado en miles de barriles.

---

## Proyecto 4: Análisis y Modelado de Procesos en la Industria Extractiva

Se trabaja con un dataset indexado por fecha y hora que contiene mediciones y cálculos de procesos industriales, con conjuntos de entrenamiento y prueba que difieren en características disponibles.

Las tareas principales incluyen:

- Validar el cálculo de recuperación de la característica `rougher.output.recovery` y comparar con valores reales.
- Analizar características ausentes en el conjunto de prueba.
- Realizar análisis estadístico y visual de concentraciones y tamaños de partículas.
- Detectar y eliminar valores atípicos en las muestras.
- Construir y evaluar modelos predictivos usando validación cruzada.
- Implementar una función para calcular el error simétrico porcentual medio (sMAPE).
- Seleccionar y probar el mejor modelo con datos de prueba.

---
