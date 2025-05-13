# Segmentación y Clasificación de Enfermedades en Hojas de Aguacate 🍃

Este repositorio contiene un proyecto completo de análisis automatizado de imágenes de hojas de aguacate mediante aprendizaje automático. Se entrena un modelo Random Forest sobre valores RGB para clasificar píxeles en tres clases: **enfermo (1)**, **sano (2)** y **fondo (3)**.

## 📁 Estructura del repositorio

- `notebooks/`: Contiene los Notebooks del proceso completo.
- `data/`: Incluye las imágenes originales, procesadas, y los datos de entrenamiento.
- `docs/`: Artículo y presentación del proyecto final.
- `README.md`: Este archivo.

## 🛠️ Tecnologías usadas

- Python 3.10
- scikit-learn
- matplotlib
- pandas
- numpy
- scikit-image

## 📊 Flujo de trabajo

1. **Extracción de puntos RGB** desde imágenes etiquetadas.
2. **Entrenamiento** de modelo Random Forest con búsqueda de hiperparámetros.
3. **Evaluación del modelo** con métricas y matriz de confusión.
4. **Segmentación automática** de nuevas imágenes y cálculo de porcentajes de enfermedad.
5. **Exportación de resultados** visuales y tabulares.

## 📎 Resultados

El modelo logró una alta precisión en la clasificación de píxeles, permitiendo generar mapas de segmentación útiles para la toma de decisiones en manejo fitosanitario del cultivo de aguacate.

## 📄 Créditos

Proyecto desarrollado por Jayder Andres Juagibioy Satiaca; Sara Gallego Thorne & Yeison Arango Ospina, estudiantes de Ingeniería Agronómica en la Universidad EAFIT, como parte del curso de Big Data y Bioinformática (2025-I).

---
