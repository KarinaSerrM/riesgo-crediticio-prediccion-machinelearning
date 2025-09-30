# Predictive Credit Risk Analysis  

Este proyecto desarrolla un **modelo de machine learning para predecir el incumplimiento de pago de clientes bancarios**, utilizando el dataset `BD_bancaria.csv`.  
El objetivo es identificar **clientes de alto riesgo** y optimizar las decisiones crediticias a través de técnicas de **análisis exploratorio, imputación de datos, visualización y modelado predictivo**.  

---

## Contenido del Proyecto  

- **EDA y Limpieza de Datos**  
  - Análisis exploratorio con `ydata_profiling`.  
  - Imputación de valores faltantes con **KNN Imputer**.  
  - Detección de outliers con método **IQR**.  

- **Modelado Predictivo**  
  - Algoritmos: **Regresión Logística, Árbol de Decisión y Random Forest**.  
  - Selección del mejor modelo basado en **AUC**.  
  - Evaluación con métricas: Accuracy, Recall, F1-Score y AUC.  

- **Resultados Clave**  
  - `Random Forest` obtuvo el mejor desempeño con un **AUC ≈ 0.86**.  
  - Curvas **ROC** generadas y guardadas en `/roc_curves`.  

- **Producción y Scoring**  
  - Modelo y escalador guardados en `/output/`.  
  - Función `score_cliente()` que permite calcular la probabilidad de incumplimiento para un nuevo cliente.  

---

## Visualizaciones  

- Distribución de la variable objetivo (`IncumplimientoPago`).  
- Matriz de correlación entre variables.  
- Curvas **ROC** de cada modelo.  

---

## Tecnologías Utilizadas  

- **Lenguaje:** Python 3.x  
- **Librerías:**  
  - `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`  
  - `scikit-learn` (ML & métricas)  
  - `ydata_profiling` (EDA automático)  
  - `joblib` (persistencia de modelos)  

---

 
