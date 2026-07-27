# Predicción del rendimiento académico de estudiantes

## Descripción

Este proyecto implementa modelos de Machine Learning supervisado para analizar el rendimiento académico de estudiantes.

Se desarrollaron dos tipos de modelos:

- Clasificación para predecir si un estudiante aprobará o reprobará.
- Regresión para estimar la calificación final del estudiante.

## Integrantes

- David Casas 22607
- Devany Zapata 22634
- Alexis Quintero 22630
- Ángel Loza 22624

## Variables utilizadas

Las variables de entrada son:

- Promedio parcial
- Asistencia
- Horas de estudio
- Accesos a Moodle
- Tareas entregadas

Las variables objetivo son:

- Resultado para clasificación
- Calificación final para regresión

## Herramientas

- Microsoft Excel
- Google Colab
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- GitHub

## Algoritmos de clasificación

- Regresión Logística
- Árbol de Decisión
- Random Forest

## Algoritmos de regresión

- Regresión Lineal
- Decision Tree Regressor
- Random Forest Regressor

## Resultados principales

### Clasificación

El mejor modelo fue la Regresión Logística.

- Accuracy: 0.9250
- Precision: 0.9565
- Recall: 0.9167
- F1-score: 0.9362

### Regresión

El mejor modelo fue la Regresión Lineal.

- MAE: 4.1919
- MSE: 31.8941
- RMSE: 5.6475
- R²: 0.9229

## Estructura del repositorio

```text
Proyecto_MachineLearning/
├── Dataset/
│   └── alumnos.csv
├── Clasificacion/
│   └── clasificacion.ipynb
├── Regresion/
│   └── regresion.ipynb
├── Imagenes/
├── Documentacion/
│   └── Reporte.pdf
└── README.md
```

## Instrucciones de ejecución

1. Descargar o clonar el repositorio.
2. Abrir el notebook correspondiente en Google Colab.
3. Ejecutar las celdas en orden.
4. Cargar el archivo alumnos.csv cuando el notebook lo solicite.
5. Revisar las métricas, gráficas y predicciones generadas.

## Conclusión

La Regresión Logística y la Regresión Lineal presentaron los mejores resultados.

El promedio parcial fue la variable con mayor influencia en ambos problemas, seguido por las tareas entregadas y la asistencia.

Los modelos pueden utilizarse como herramientas de apoyo para detectar estudiantes en riesgo académico y realizar intervenciones tempranas.
