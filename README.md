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

## 7. Comprobar los notebooks

Antes de dar por terminado el repositorio:

1. Abre `clasificacion.ipynb` en Colab.
2. Selecciona **Entorno de ejecución → Reiniciar sesión**.
3. Ejecuta **Ejecutar todo**.
4. Comprueba que no aparezcan errores.
5. Repite con `regresion.ipynb`.

Esto es importante porque a veces el notebook funciona únicamente porque quedaron variables guardadas de ejecuciones anteriores. Reiniciar el entorno revela esos pequeños fantasmas de Colab.

## 8. Verificar el repositorio

Revisa que:

- `alumnos.csv` tenga 200 registros.
- Los notebooks tengan resultados visibles.
- Las imágenes puedan abrirse.
- El PDF pueda descargarse.
- El README aparezca en la portada del repositorio.
- No existan archivos llamados `Untitled.ipynb`.
- El repositorio sea público o el profesor tenga acceso.
- El enlace funcione desde una ventana de incógnito.

## Evidencias que necesitarás

Para la Fase 8 basta con estas tres:

### Evidencia 1. Estructura final del repositorio

Captura donde se observen las carpetas y archivos principales.

### Evidencia 2. Archivo README

Captura de la portada del repositorio mostrando la descripción y los resultados.

### Evidencia 3. Ejecución de los notebooks

Captura de los notebooks abiertos en Colab sin errores o mostrando las tablas finales.

Primero debes crear y subir `clasificacion.ipynb` y `regresion.ipynb`; después continúas con las imágenes, el repor