# Análisis de Sentimiento en X (Twitter) con SVM 🚀

Este proyecto desarrolla un sistema de clasificación automática para determinar si el sentimiento de un tweet sobre noticias actuales es **Positivo** o **Negativo**.

## 📊 Resumen del Proyecto
* **Dataset**: 100 tweets actuales sobre deportes, economía y tecnología, etiquetados manualmente y balanceados (50/50).
* **Modelo**: Clasificador Support Vector Machine (SVM) con kernel lineal.
* **Preprocesamiento**: Limpieza de ruido (hashtags, menciones, números) y aplicación de *stopwords* en español.
* **Rendimiento**: **70% de precisión (Accuracy)** en el conjunto de prueba.

## 🧠 Aprendizajes Técnicos y Desafíos
El proyecto destaca por el análisis de la **IA explicable (XAI)** y la gestión de datos escasos:

1.  **El Desafío de los Datos**: Inicialmente, con 50 tweets, el modelo presentaba un sesgo basado en palabras vacías (conectores). Al eliminarlas (*stopwords*), la precisión cayó al 27%.
2.  **Optimización**: Al ampliar la muestra a 100 tweets, el modelo logró capturar patrones semánticos reales, elevando la precisión al 70% incluso con una limpieza estricta de texto.
3.  **Interpretación del Modelo**: Se identificaron las palabras con mayor peso emocional para el algoritmo:
    * **Positivo**: *"inversión"*, *"gracias"*, *"mundial"*, *"acuerdo"*.
    * **Negativo**: *"causa"*, *"afecta"*, *"huelga"*, *"vuelve"*.

## 🛠️ Tecnologías Utilizadas
* **Python**
* **Pandas** (Estructura de datos)
* **Scikit-learn** (Modelo SVM y Vectorización)
* **NLTK** (Procesamiento de Lenguaje Natural)
* **Matplotlib & Seaborn** (Visualización de métricas)

## 🚀 Cómo ejecutarlo
1. Clona este repositorio. `git clone repositorio`
2. Asegúrate de tener instaladas las dependencias: `pip install pandas scikit-learn matplotlib seaborn nltk`.
3. Abre el archivo `.ipynb` en Jupyter Notebook o VS Code y ejecuta todas las celdas para reproducir la matriz de confusión y el reporte de clasificación.

---
**Autor:** Alejandro Tacoronte González
**LinkedIn:** [https://www.linkedin.com/in/alejandrotacoronte/]