# Preprocesamiento y Escalamiento de Datos - RetailData Analytics

Este proyecto presenta un flujo de trabajo completo para la limpieza y transformación de datos demográficos y de comportamiento de clientes. El objetivo es preparar un dataset crudo para ser utilizado en modelos predictivos de Machine Learning.

## 🚀 Contenido del Notebook
El análisis cubre las siguientes etapas críticas:
* **Imputación de Valores Faltantes:** Uso de la media para tratar nulos en variables numéricas.
* **Codificación Categórica:** Implementación de *Label Encoding*, *One-Hot Encoding* y *Variables Dummy* (evitando la trampa de la multicolinealidad).
* **Escalamiento Numérico:** Aplicación de *Normalización Min-Max* y *Estandarización Z-Score*.

## 🛠️ Tecnologías Utilizadas
* Python 3.x
* Pandas & Numpy
* Scikit-Learn (SimpleImputer, StandardScaler, MinMaxScaler, etc.)

## 📊 Resultados
El proyecto genera un dataset final estandarizado y listo para ser procesado por algoritmos basados en distancias (como KNN o SVM) o regresiones lineales.
