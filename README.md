# Predicción de precios de Airbnb - Práctica de Machine Learning

Este proyecto forma parte de la práctica final del módulo de Machine Learning del Bootcamp de KeepCoding. El objetivo es construir un pipeline completo de regresión que permita predecir el precio de alojamientos de Airbnb en Madrid, aplicando buenas prácticas de limpieza, análisis, preprocesamiento y modelado.

## 📌 Objetivo

Predecir el precio (`Price`) de alojamientos de Airbnb utilizando un enfoque de Machine Learning, priorizando la correcta aplicación del proceso de ciencia de datos por encima de la obtención de métricas perfectas.

## 🧰 Tecnologías y herramientas

- Python 3.10
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🗂️ Estructura del proyecto

- `practica_ml.ipynb`: Notebook principal con todo el análisis paso a paso.
- `environment.yml`: Entorno Conda exportado para replicar el entorno.
- `data/`: Carpeta donde debe colocarse el archivo CSV con los datos originales (no incluido por privacidad).

## 🔄 Pipeline aplicado

1. **División temprana** del dataset en `train` y `test`.
2. **Análisis exploratorio (EDA)**:
   - Estadísticas descriptivas
   - Visualización de outliers
   - Correlaciones
3. **Preprocesamiento**:
   - Eliminación de columnas irrelevantes o con muchos nulos
   - Ingeniería de variables
   - Escalado de numéricas y codificación one-hot en pipeline
4. **Modelado**:
   - Comparación entre regresión lineal, Ridge y Lasso
   - Validación cruzada 
   - Métrica: RMSE sobre `log_price`
5. **Evaluación y conclusión escrita**

## ▶️ Cómo ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/dftomatis/keepcoding_ml
   cd tu-repo
   ```

2. Crea el entorno Conda desde el archivo:
   ```bash
   conda env create -f environment.yml
   conda activate ml_practica
   ```

3. Inicia Jupyter:
   ```bash
   jupyter notebook
   ```

## 📋 Requisitos del entorno

El archivo `environment.yml` contiene todas las dependencias necesarias para ejecutar el notebook. Incluye:
- Python 3.10
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, etc.

## 📄 Licencia

Este proyecto es parte de una práctica educativa y no tiene fines comerciales.  
© 2025 - Ing. Darío Tomatis
