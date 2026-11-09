# Fundamentos de Machine Learning - Workshop 2: Modelos Supervisados

Este repositorio contiene los talleres prácticos de **Machine Learning Supervisado** desarrollados para la asignatura **Fundamentos de Machine Learning** en la **Universidad EAFIT**.

Se abarcan dos problemas fundamentales del aprendizaje automático: **Regresión** y **Clasificación**, implementando flujos de trabajo completos de ciencia de datos: Análisis Exploratorio (EDA), preprocesamiento, ingeniería de características, entrenamiento de múltiples algoritmos, ajuste de hiperparámetros y evaluación de desempeño con métricas especializadas.

---

## 📂 Contenido del Proyecto

- **`Clasificación.ipynb`**:
  - Preprocesamiento de variables categóricas y normalización numérica.
  - Manejo y balanceo de datos.
  - Implementación y comparativa de clasificadores: *Regresión Logística, Random Forest, Support Vector Machines (SVM), Árboles de Decisión y XGBoost/Gradient Boosting*.
  - Métricas de evaluación: Matriz de confusión, Accuracy, Precision, Recall, F1-Score y curvas ROC-AUC.

- **`Regresion.ipynb`**:
  - Análisis estadístico univariado y multivariado de variables predictoras.
  - Detección y tratamiento de outliers / valores atípicos.
  - Modelos predictivos: *Regresión Lineal Múltiple, Ridge/Lasso (regularización), Random Forest Regressor y Modelos Basados en Ensembles*.
  - Métricas de evaluación: RMSE (Root Mean Squared Error), MAE (Mean Absolute Error) y R² (Coeficiente de determinación).

- **`Workshop2_ML.pdf`**: Documento con las pautas formales, formulación del problema y requerimientos analíticos del taller.

---

## 🛠️ Tecnologías y Librerías

- **Lenguaje:** Python 3.10+
- **Ciencia de Datos & ML:** Scikit-Learn, NumPy, Pandas, SciPy
- **Visualización:** Matplotlib, Seaborn
- **Entorno:** Jupyter Notebook

---

## 🚀 Cómo Ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/JerFGa/FundamentosML-Workshop2.git
   cd FundamentosML-Workshop2
   ```

2. Crear y activar un entorno virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```

3. Instalar dependencias:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

4. Lanzar Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
