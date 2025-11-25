#  Predicción de Propinas con Machine Learning  
Proyecto completo de análisis, modelado y comparación de algoritmos usando el **Tips Dataset**.

---

##  Descripción del Proyecto
Este proyecto aplica técnicas de **Machine Learning supervisado** para predecir el valor de la propina (`tip`) en un restaurante utilizando características como:

- Cuenta total (`total_bill`)
- Sexo del cliente
- Fumador / No fumador
- Día de la semana
- Momento del día
- Tamaño del grupo (`size`)

El objetivo es comparar distintos modelos y seleccionar el que obtiene el mejor desempeño.

---

##  Estructura del Proyecto




---

##  Tecnologías y Librerías Usadas

- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  
- Pipeline + ColumnTransformer  

---

##  Preprocesamiento Aplicado

El dataset pasa por un procesamiento automático mediante **Pipeline**, que incluye:

- Escalado de variables numéricas (StandardScaler)
- One-Hot Encoding para variables categóricas
- División entrenamiento/prueba (80% - 20%)

---

##  Modelos Entrenados y Comparados

Se probaron los siguientes algoritmos:

1. **Regresión Lineal**
2. **Árbol de Decisión**
3. **Random Forest**
4. **KNN Regression**

Cada modelo se evaluó usando:

- R² (Coeficiente de determinación)
- MAE (Error Absoluto Medio)
- RMSE (Raíz del Error Cuadrático Medio)
- Validación cruzada (5-Fold)

---

