# 🏦 Análisis de Riesgo Crediticio

Este proyecto aplica **Data Science y Machine Learning** al problema de predicción de riesgo crediticio.  
Se desarrolla un flujo completo: **EDA → Preprocesamiento → Modelado → Evaluación → Recomendaciones**.

---

## 🎯 Objetivo
Predecir el incumplimiento de préstamos y entender qué factores (ingresos, DTI, calificación, propiedad, etc.) impactan más en el riesgo crediticio.

---

## 📊 Dataset
- Fuente: {colocar link o descripción del dataset}
- Variables destacadas: ingreso anual, DTI, monto de préstamo, tasa de interés, grado crediticio, propiedad de vivienda.
- Limpieza: tratamiento de valores nulos, outliers, codificación de variables categóricas, balanceo con SMOTE.

---

## 🧠 Metodología
1. **EDA**: visualización de distribuciones, correlaciones y patrones de riesgo.  
2. **Preprocesamiento**: escalado, PCA, balanceo de clases.  
3. **Modelos entrenados**:  
   - Logistic Regression  
   - Random Forest  
   - Gradient Boosting  
   - XGBoost  
   - Voting Classifier (ensemble)  
4. **Validación**: train/test split, métricas de clasificación.

---

## 📈 Resultados
- **AUC**: 0.942  
- **Precisión en test**: {completar con tu valor}  
- **Insights**:  
  - La consolidación de deudas es el principal motivo de préstamos.  
  - Propietarios hipotecados reciben montos más altos.  
  - Grados A y B son los más favorecidos por las instituciones.  
  - Ingresos altos por sí solos no predicen bajo riesgo.  

---

## 🎥 Presentación
Incluye un resumen ejecutivo del proyecto con visualizaciones y hallazgos:  
[📑 Ver presentación (PDF)](Riesgo.pdf)

---

## 🚀 Ejecución
- Abrir en Colab: [![Open In Colab](https://colab.research.google.com/drive/1WIw72Euw3c0BeaBlAUmm82ilSMDb-EGT?usp=sharing)] 
- O clonar este repositorio y abrir `Riesgo_Crediticio.ipynb`.

---

## ⚖️ Licencia
MIT License
