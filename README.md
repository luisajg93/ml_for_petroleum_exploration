# ml_for_petroleum_exploration
Creación de un modelo de machine learning reforzado con bootstrapping para elegir la mejor región para inversión petrolera. ***Proyecto desarrollado como evaluación final del Sprint Aprendizaje automático en negocios del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
Trabajas en la compañía de extracción de petróleo OilyGiant. Tu tarea es encontrar los mejores lugares donde abrir 200 pozos nuevos de petróleo.

Condiciones:

- Solo se debe usar la regresión lineal para el entrenamiento del modelo.
- Al explorar la región, se lleva a cabo un estudio de 500 puntos con la selección de los mejores 200 puntos para el cálculo del beneficio.
- El presupuesto para el desarrollo de 200 pozos petroleros es de 100 millones de dólares.
- Un barril de materias primas genera 4.5 USD de ingresos. El ingreso de una unidad de producto es de 4500 dólares (el volumen de reservas está expresado en miles de barriles).
- Después de la evaluación de riesgo, mantén solo las regiones con riesgo de pérdidas inferior al 2.5%. De las que se ajustan a los criterios, se debe seleccionar la región con el beneficio promedio más alto.

## Objetivo del proyecto
Encontrar con ayuda de un modelo de machine learning la mejor región para abrir 200 pozoz nuevos de petroleo.

## Modelos de machine learning creados
- Linear Regression

## Librerías principales utilizadas
- pandas
- matplotlib
- seaborn
- numpy
- sklearn
- warnings

## Resultados
- En este proyecto se demuestra el uso y beneficio de la técnica de bootstrapping para la elección de menor riesgo.
- En el archivo "proyecto_10" se pueden revisar cada paso del proyecto, desde el EDA hasta la selección de las regiones óptimas para inversión.