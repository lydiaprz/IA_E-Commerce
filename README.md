# IA_E-Commerce: Predicción de Beneficios con Machine Learning

Este repositorio contiene mi **Proyecto Final** centrado en el desarrollo de un algoritmo de **aprendizaje supervisado** para predecir el beneficio (`Profit`) de ventas en un entorno e-commerce. El proyecto se basa en los principios y ejemplos técnicos del curso de IA de **fmgarcia**.

## 📊 Descripción del Proyecto
El objetivo principal es implementar un modelo predictivo que permita a las empresas del sector e-commerce estimar la rentabilidad de sus transacciones basándose en datos históricos como ventas, cantidad de productos y ubicación geográfica.

El proyecto está desarrollado íntegramente en **Jupyter Notebooks (100.0%)**.

## 📂 Estructura del Repositorio
Siguiendo una organización modular [2], el repositorio se divide en:

*   **`data/`**: Contiene el dataset original (`ecommerce.csv`) y la versión procesada lista para el modelo (`ecommerce_prepared.csv`).
*   **`notebooks/`**: Cuadernos de trabajo divididos por fases:
    1.  **Análisis Exploratorio (EDA):** Visualización y limpieza inicial.
    2.  **Preprocesamiento:** Transformación de variables, escalado (StandardScaler) y codificación (OneHotEncoder).
    3.  **Modelado:** Entrenamiento de modelos de Regresión Lineal y Random Forest.
*   **`requirements.txt`**: Listado de dependencias necesarias (Pandas, Scikit-Learn, Matplotlib, Seaborn).

## 🛠️ Instalación y Uso
Para ejecutar este proyecto localmente, sigue estos pasos:

1. **Clonar el repositorio**:
   ```
   git clone https://github.com/lydiaprz/IA_E-Commerce.git
   ```
2. Instalar dependencias:
3. Ejecutar los notebooks: Abre los archivos en la carpeta notebooks/ siguiendo el orden numérico.

## 🚀 Conclusiones
Tras el entrenamiento y evaluación de los modelos, se determinó que el Random Forest Regressor ofrece una mayor precisión al capturar relaciones no lineales complejas, siendo la herramienta recomendada para la predicción de beneficios en este dataset.

## 👤 Autora
• Lydia Pérez - lydiaprz
