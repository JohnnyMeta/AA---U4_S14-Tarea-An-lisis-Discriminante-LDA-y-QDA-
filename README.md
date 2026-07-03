# Análisis Discriminante (LDA y QDA) sobre el Wine Dataset

Proyecto desarrollado para la asignatura de **Aprendizaje Automático**, en el que se implementan y comparan los algoritmos de **Linear Discriminant Analysis (LDA)** y **Quadratic Discriminant Analysis (QDA)** utilizando el **Wine Dataset** de Scikit-learn.

El análisis se realiza utilizando el conjunto de datos en su estado original, **sin aplicar técnicas de preprocesamiento**, con el objetivo de evaluar el comportamiento real de ambos modelos sobre datos crudos.

---

# Objetivos

- Cargar el Wine Dataset sin modificaciones.
- Realizar un análisis exploratorio de los datos (EDA).
- Visualizar las características principales del conjunto de datos.
- Implementar el algoritmo LDA.
- Implementar el algoritmo QDA.
- Comparar ambos modelos mediante métricas de clasificación.
- Contrastar su desempeño con otros algoritmos de Machine Learning.
- Visualizar las fronteras de decisión.
- Analizar los resultados obtenidos.

---

# Dataset

Se utiliza el **Wine Dataset**, incluido en la librería Scikit-learn.

Este conjunto de datos contiene análisis químicos realizados sobre vinos provenientes de tres variedades diferentes cultivadas en Italia.

### Características del dataset

- 178 muestras
- 13 variables numéricas
- 3 clases de vinos

El dataset fue cargado mediante:

```python
from sklearn.datasets import load_wine
```

---

# Contenido del proyecto

El notebook se divide en las siguientes etapas:

## Descripción del conjunto de datos

- Carga del Wine Dataset
- Información general
- Variables disponibles
- Distribución de clases

---

## Exploración de datos (EDA)

Se realiza una exploración inicial sin modificar los datos:

- dimensiones
- tipos de datos
- estadísticas descriptivas
- valores faltantes
- distribución de clases

---

## Visualización

Se generan distintas visualizaciones para comprender el comportamiento de las variables.

Entre ellas:

- histogramas
- distribuciones
- gráficos exploratorios

---

## Preparación de datos

Se realiza únicamente:

- separación entre entrenamiento y prueba

No se aplican técnicas como:

- normalización
- estandarización
- eliminación de outliers
- selección de características

Esto permite evaluar el rendimiento de los algoritmos sobre datos originales.

---

## Entrenamiento de modelos

Se implementan los siguientes modelos:

### Linear Discriminant Analysis (LDA)

Modelo lineal que asume:

- distribución normal
- matrices de covarianza iguales entre clases

---

### Quadratic Discriminant Analysis (QDA)

Modelo cuadrático que permite:

- una matriz de covarianza distinta para cada clase
- fronteras de decisión no lineales

---

## Comparación adicional

Además del análisis entre LDA y QDA, el notebook incluye una comparación con otros algoritmos de clasificación para tener un punto de referencia del rendimiento obtenido.

---

## Evaluación de resultados

Se comparan los modelos utilizando métricas como:

- Accuracy
- Precision
- Recall
- F1-Score
- Matriz de confusión

También se analiza el tiempo de entrenamiento de cada modelo.

---

## Fronteras de decisión

Se representan gráficamente las fronteras de decisión de:

- LDA
- QDA

permitiendo observar visualmente cómo separan las diferentes clases del conjunto de datos.

---

## Conclusiones

Finalmente se presentan las conclusiones obtenidas sobre:

- desempeño de LDA
- desempeño de QDA
- diferencias entre ambos modelos
- comportamiento sobre datos sin tratamiento

---

# Librerías utilizadas

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- time

---

# Ejecución

1. Clonar el repositorio.

```bash
git clone https://github.com/JohnnyMeta/AA---U4_S14-Tarea-An-lisis-Discriminante-LDA-y-QDA-.git
```

2. Instalar las dependencias.

```bash
pip install -r requirements.txt
```

o instalar manualmente:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Ejecutar el notebook:

```
Ortíz_Johnny_U4_S14_Tarea_Análisis_Discriminante_(LDA_y_QDA).ipynb
```

---

# Conceptos abordados

- Aprendizaje Supervisado
- Clasificación Multiclase
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Evaluación de modelos
- Visualización de datos
- Fronteras de decisión
- Machine Learning con Scikit-learn

---

# Autor

**Johnny Ortíz**

Proyecto desarrollado como parte de la asignatura **Aprendizaje Automático**.
