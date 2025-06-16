# Proyecto Capstone MBD

**Maestría:** Maestría en Inteligencia de Negocios y Ciencia de Datos  
**Universidad:** Universidad de Las Américas  
**Nombre del estudiante:** Lissette Granizo  
**Título del proyecto:** Análisis predictivo de ventas por producto para la prevención de quiebre de stock en las tiendas de Walmart

---

## 📌 Descripción General

Este repositorio contiene el código, análisis y resultados desarrollados como parte del proyecto de titulación de la Universidad de Las Américas. El objetivo del trabajo es anticipar la demanda de productos en tiendas Walmart utilizando técnicas de análisis predictivo, con el propósito de prevenir quiebres de stock, optimizar inventario y reducir los costos operativos asociados a una gestión ineficiente.

---

## 🎯 Problema a Resolver

El sistema actual de planificación de inventario en Walmart presenta limitaciones para proyectar con precisión la demanda futura, lo que ha generado pérdidas en ventas y quiebres frecuentes de stock. La investigación busca resolver esta problemática mediante la aplicación de modelos estadísticos y de machine learning, permitiendo una toma de decisiones más informada y proactiva.

---

## 🔧 Modelos Utilizados

- **ARIMA y SARIMA**: Para pronóstico de series temporales de ventas mensuales por producto.  
- **Random Forest**: Para mejorar la precisión predictiva en productos con demanda irregular.  
- **Evaluación de modelos con métricas**: MAE, RMSE, Recall y F1-score.

---

## 📂 Base de Datos

Se trabajó con el archivo `WalmartData_Limpio.csv`, el cual contiene registros históricos de ventas, incluyendo fecha de transacción, producto, cantidad vendida, precio unitario, demanda real y variables logísticas relevantes.

---

## 📈 Contenido del Proyecto

- Limpieza y preprocesamiento de datos: Normalización, tratamiento de valores nulos y codificación de variables categóricas.  
- Análisis exploratorio (EDA): Identificación de patrones estacionales, correlaciones y productos críticos.  
- Modelado estadístico y evaluación: Comparación de rendimiento de modelos predictivos por producto.  
- Visualización de resultados: Gráficos de error, quiebres de stock y demanda vs. precio.

---

## 🧪 Resultados y Recomendaciones

- SARIMA y Random Forest presentaron el mejor desempeño general, con menor error y mayor sensibilidad para identificar quiebres de stock.  
- Se identificaron productos de alto riesgo operativo como *Tablet, Fridge, Washing Machine* y *TV*, los cuales requieren ajustes inmediatos en sus niveles de stock y políticas de reabastecimiento.  
- Se recomienda automatizar la planificación de inventario con base en las predicciones generadas, complementado con alertas tempranas que permitan decisiones oportunas.

---

## 🧠 Cómo usar este proyecto

1. Abrir el archivo `Tesis_LG.ipynb` en Jupyter Notebook.  
2. Ejecutar las celdas en orden: limpieza, EDA, modelado, evaluación y visualización.  
3. Analizar las recomendaciones por producto con base en el modelo óptimo y aplicar estrategias de reabastecimiento.

---

## 🧾 Requisitos

```bash
Python 3.x
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn openpyxl
```

---

## 📌 Contribución

Proyecto desarrollado por **Lissette Granizo** como trabajo final de titulación para la Maestría en Inteligencia de Negocios y Ciencia de Datos en la Universidad de Las Américas (UDLA).  
Agradecimientos al Ing. Manuel Eugenio Morocho por su guía académica.
