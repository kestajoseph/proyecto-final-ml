# Proyecto Final – Machine Learning sobre Proyecto de Viandas

Este proyecto forma parte de la **entrega final** del curso de Data Science.  
Es una **continuación del Proyecto de Viandas** trabajado en entregas anteriores, donde se realizaron análisis exploratorios y visualizaciones.  

En esta entrega, se aplica **Machine Learning** para predecir si una venta pertenece a la categoría de *alta ganancia* o *baja ganancia*, utilizando el mismo dataset gastronómico.

---

## 📂 Archivos incluidos
- `ProyectoParcial+Joseph.ipynb`: Notebook en Python/Colab con todo el flujo de trabajo (feature selection, entrenamiento, métricas y conclusiones).  
- `gastro_demo.csv`: Dataset utilizado, basado en ventas de un proyecto gastronómico de viandas.  

---

## 📊 Objetivo
Entrenar un modelo de Machine Learning capaz de **clasificar ventas** en dos categorías:  
- **Alta ganancia** (ganancia ≥ mediana)  
- **Baja ganancia** (ganancia < mediana)  

---

## ⚙️ Metodología
1. **Preprocesamiento de datos** (imputación, escalado, codificación categórica).  
2. **Selección de características** usando `SelectKBest` con información mutua.  
3. **Entrenamiento** de un modelo de Regresión Logística.  
4. **Evaluación** con métricas de clasificación.  
5. **Conclusiones** con interpretación de resultados y propuestas de mejora.  

---

## 📈 Resultados
- **Accuracy:** 0.82  
- **Precision:** 0.79  
- **Recall:** 0.76  
- **F1 Score:** 0.77  

El modelo logra un desempeño aceptable para identificar casos de alta ganancia.  
Las variables más influyentes fueron **precio, costo y método de pago**.  

---

## 📌 Conclusiones
Este proyecto demuestra cómo un mismo dataset (Proyecto de Viandas) puede usarse primero para **análisis exploratorio** y luego para **modelado predictivo**.  
El modelo de Regresión Logística mostró resultados consistentes y abre la puerta a futuras mejoras, como:  
- Probar modelos más avanzados (Random Forest, SVM).  
- Ajustar hiperparámetros.  
- Incorporar datos externos (ej.: promociones, clima, estacionalidad).  

---

## 🚀 Autor
**Kesta Joseph**  
