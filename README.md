# iaupb_examen_03

## Examen No. 3 – Aprendizaje Supervisado: Comparación de Algoritmos de Clasificación

---

## Información del Estudiante

| Campo | Detalle |
|---|---|
| **Nombre completo** | Juan Jose Arango |
| **Código estudiantil** | 000549306 |
| **Correo institucional** | juan.arangoo@upb.edu.co |
| **Programa** | Ingeniería en Sistemas |

---

## Información del Curso

| Campo | Detalle |
|---|---|
| **Universidad** | Universidad Pontificia Bolivariana |
| **Curso** | Inteligencia Artificial |
| **Docente** | Juan Darío Rodas |
| **Periodo** | 202610 |
| **Fecha de entrega** | Viernes 27 de marzo de 2026, 8:00 pm (GMT-5) |

---

## Descripción del Repositorio

Este repositorio contiene la solución al Examen No. 3 del curso de Inteligencia Artificial, cuyo objetivo es comparar el desempeño de tres algoritmos de clasificación supervisada aplicados al dataset **Palmer Penguins** del archipiélago Antártico.

### Problema

Clasificar la especie de pingüino (Adelie, Chinstrap o Gentoo) a partir de 6 características morfológicas y geográficas, utilizando los siguientes algoritmos:

- **Logistic Regression**
- **Random Forest**
- **Support Vector Machine (SVM)**

### Dataset

- **Fuente:** [Palmer Penguins – UCI ML Repository](https://archive.ics.uci.edu/dataset/690/palmer+penguins-3)
- **Filas:** 344 ejemplares
- **Características:** 6 (bill_length_mm, bill_depth_mm, flipper_length_mm, body_mass_g, island, sex)
- **Variable objetivo:** species (3 clases)

---

## Contenido del Repositorio

```
iaupb_examen_03/
│
├── iaupb_examen_03_clasificacion.ipynb   # Solución completa en Jupyter Notebook
└── README.md                             # Este archivo
```

### Contenido del Notebook

1. Importación de librerías
2. Carga y exploración inicial del dataset
3. EDA – Análisis exploratorio y calidad de datos
   - Distribución de clases
   - Boxplots por variable numérica y especie
   - Matriz de correlación (heatmap)
4. Preprocesamiento (sin data leakage)
   - División train/test 80-20, random_state=42
   - Imputación · One-Hot Encoding · StandardScaler
5. Entrenamiento de los tres modelos
6. Evaluación de métricas (accuracy, precision, recall, F1-score)
7. Matrices de confusión individuales
8. Comparación visual de métricas
9. Selección del mejor modelo
10. Preguntas de análisis e interpretación (7 preguntas)

---

## Entorno de Implementación

El notebook fue desarrollado y ejecutado en **Google Colab** (Python 3).

### Librerías principales utilizadas

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `palmerpenguins`
