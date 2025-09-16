# Proyecto: Comparación de Modelos de Aprendizaje Supervisado para regresión y clasificacion.

## Autor
juan david parra sierra             NRC 000475676
Facultad de ciencias exactas, escuela de ingenierias.
Ingenieria en sistemas e informatica.


## 📌 Descripción General
Este proyecto implementa y compara tres algoritmos de aprendizaje supervisado para resolver problemas de regresión y clasificacion:

- **Linear Regression**
- **Random Forest Regressor**
- **Support Vector Regression (SVR)**

- **Logistic Regression**
- **Random Forest**
- **Support version Machine (SVM)**

---

## 🗂 Estructura del Proyecto
El proyecto está contenido en archivos Jupyter Notebook con las siguientes secciones:

### 1. Carga y Exploración Inicial
- Importación de librerías.  
- Descarga del dataset desde UCI.  
- Análisis de dimensiones, tipos de datos, valores únicos y estadísticas descriptivas.  
- Detección de valores faltantes.

### 2. Análisis Exploratorio de Datos (EDA)
- Visualización de distribuciones (histogramas, boxplots).  
- Matriz de correlación entre características.  
- Análisis de la variable objetivo.

### 3. Preprocesamiento de Datos
- Escalado de características con `StandardScaler`.  
- Codificación de variables categóricas (en caso de existir).  
- División en conjuntos de entrenamiento y prueba.

### 4. Entrenamiento de Modelos
Implementación de los tres algoritmos:

### 5. Evaluación de Modelos
Métricas utilizadas:
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **R² Score**  

Se incluye validación cruzada para mayor robustez.

### 6. Comparación y Conclusiones
- Análisis comparativo del rendimiento de los modelos.  
- Visualizaciones de resultados (gráficos de residuales, predicciones vs reales).  
- Recomendación sobre el modelo más adecuado para el problema.

---

## 🛠 Tecnologías Utilizadas
- **Lenguaje:** Python 3.12  
- **Librerías:**  
  - `pandas`, `numpy`  
  - `matplotlib`, `seaborn`  
  - `scikit-learn`  
  - `ucimlrepo` (para descarga del dataset)

---

## 📈 Resultados
Cada modelo se evalúa usando varias métricas y validación cruzada.  
Se incluyen gráficos para:

- Comparación visual de predicciones.  
- Análisis de residuales.  
- Importancia de características (para Random Forest).  

---

## 📋 Notas
- El notebook está comentado en español para facilitar su comprensión.  
- Todos los pasos son reproducibles. Los resultados pueden variar ligeramente por la aleatoriedad en la división de datos o en los algoritmos.  
- Se incluyen consideraciones sobre **overfitting** y **underfitting**.

