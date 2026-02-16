Predicción de Fuga de Clientes - Interconnect Telecom

1. Descripción del Proyecto

La empresa de telecomunicaciones "Interconnect" quiere pronosticar su tasa de cancelación de clientes (Churn Rate). El objetivo es identificar a los usuarios que planean irse para ofrecerles promociones y retenerlos.

2. Objetivo

Desarrollar un modelo de Machine Learning que prediga si un cliente cancelará su servicio, permitiendo a la empresa enfocar sus recursos en retener a los clientes valiosos.

3. Herramientas Utilizadas

Lenguaje: Python

Librerías: Pandas, Matplotlib, Scikit-learn, CatBoost.

4. Proceso

Análisis de Datos: Identifiqué que los clientes con contratos mensuales y pago electrónico son los que más cancelan.

Preprocesamiento: Unifiqué 4 tablas de datos diferentes y traté los valores ausentes.

Modelado: Probé varios algoritmos (Random Forest, CatBoost).

5. Resultados

El modelo final logró un AUC-ROC de 0.89 (ajusta este número al tuyo), lo que significa que tiene una alta capacidad para distinguir entre clientes leales y los que se van.

Proyecto realizado por Yury Ccotaccallapa para el Bootcamp de Data Science.
