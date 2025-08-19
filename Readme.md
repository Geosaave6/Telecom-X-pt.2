# 📊 Challenge Telecom X - Parte 2  
**Predicción de Evasión de Clientes (Churn Prediction)**  

---

## 👤 Autor  
- **Nombre:** Geovanni Saavedra  
- **Fecha:** 19/08/2025  

---

## 📌 Descripción  
Este proyecto corresponde a la **segunda parte** del Challenge de **Telecom X**.  
El objetivo es **predecir la evasión de clientes (churn)** utilizando técnicas de **machine learning**.  

Se construyó un modelo basado en **Regresión Logística**, aplicando un flujo completo de análisis:  

1. **Carga y exploración de datos** (`TelecomX_Data.json`).  
2. **Análisis exploratorio de la variable objetivo (Churn)**.  
3. **Preprocesamiento de variables categóricas y numéricas**.  
4. **Normalización de datos y división en entrenamiento y prueba**.  
5. **Entrenamiento de un modelo de regresión logística**.  
6. **Evaluación mediante accuracy, matriz de confusión y reporte de clasificación**.  
7. **Análisis de importancia de variables**.  
8. **Conclusiones estratégicas de negocio**.  

---

## 🛠️ Tecnologías Utilizadas  
- Python 3  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 📂 Archivos del Proyecto  
- `TelecomX_Part2.ipynb` → Notebook con el código completo.  
- `TelecomX_Data.json` → Dataset utilizado para el análisis.  
- `README.md` → Documento actual con descripción y resultados.  

---

## 📊 Resultados del Modelo  
- **Accuracy promedio:** ~80% (dependiendo de la corrida).  
- El modelo identifica patrones importantes relacionados con la **evasión de clientes**.  

Las variables más influyentes fueron:  
- Tipo de contrato.  
- Cargos mensuales.  
- Servicios adicionales.  

---

## 🚀 Conclusiones Estratégicas  
1. Los clientes con mayor riesgo de evasión suelen tener:  
   - Contratos mensuales.  
   - Facturación mensual más alta.  
   - Pocos servicios adicionales contratados.  

2. Estrategias recomendadas:  
   - Ofrecer **descuentos o promociones** para contratos a largo plazo.  
   - Incentivar la adquisición de **servicios complementarios**.  
   - Reforzar la **atención al cliente y retención** en contratos mensuales.  

---

## 📎 Uso  
1. Abrir el notebook en Google Colab o Jupyter.  
2. Asegurar que el archivo `TelecomX_Data.json` esté en la misma carpeta.  
3. Ejecutar todas las celdas para reproducir el análisis y resultados.  

---

✨ Proyecto realizado por **Geovanni Saavedra** el **19/08/2025**.  
