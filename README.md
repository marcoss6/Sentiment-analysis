# 📊 Análisis de Sentimiento en Tweets sobre ChatGPT

Este repositorio contiene un modelo de Machine Learning desarrollado para analizar el sentimiento en tweets relacionados con ChatGPT.
Se han utilizado diversas técnicas de procesamiento de lenguaje natural (NLP) como: Conversión del texto a minúsculas, Eliminación de stopwords, Tokenización (Dividir los tweets en palabras individuales), Lematización (con spaCy) y Vectorización del texto (TF-IDF) el cual convierte el texto procesado en representaciones numéricas para ser usado en modelos de Machine Learning.

También se han utilizado modelos clásicos de clasificación (**Naïve Bayes**, **SVM** y **Random Forest**) para predecir si un tweet expresa un sentimiento **positivo, negativo o neutral**.

## 📂 Contenido del repositorio
- **`EFC-SA-Marcos_Cifuentes_Suarez.ipynb`** → Notebook principal con la implementación del modelo.
- **`README.md`** → Este archivo con información sobre el proyecto.

---

## 🚀 Cómo usar este repositorio
1. Haz clic en el botón para abrir el notebook en Google Colab:  
   [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marcoss6/Sentiment-analysis/blob/main/EFC-SA-Marcos_Cifuentes_Suarez.ipynb)
2. **Cuidado con el Paso 3 (Limpieza y preprocesamiento del texto) ⚠️**  
   - **El Paso 3 tarda aproximadamente 16 minutos** en ejecutarse, ya que aplica varias técnicas de procesamiento de lenguaje natural (NLP).  
   - Si **NO quieres esperar**, puedes **cargar directamente el CSV ya procesado** desde las líneas de código escritas más abajo
   - Si decides ejecutar el preprocesamiento, puedes **guardar el CSV resultante** para evitar repetir este paso la próxima vez:  
   - **IMPORTANTE**: Asegúrate de **modificar la ruta en el código** en el caso de que quieras ejecutar y guardar el preprocesamiento en un CSV. 
3. Ejecuta todas las celdas para preprocesar los datos, entrenar los modelos y evaluar su desempeño.  
4. Puedes modificar el código para probar diferentes técnicas de NLP o ajustar hiperparámetros.  



















