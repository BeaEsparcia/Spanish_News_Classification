# Proyecto de clasificación de noticias en español

- Python
- NLTK 3.5
- Scikit-learn 0.24.2
- License: MIT

## Descripción

Este proyecto implementa un sistema de clasificación de noticias en español utilizando técnicas de Procesamiento de Lenguaje Natural (PLN) y aprendizaje automático. El objetivo es categorizar automáticamente artículos de noticias en seis categorías diferentes: cultura, deportes, economía, España, internacional y sociedad.

## Características

- Preprocesamiento de texto avanzado incluyendo tokenización, eliminación de stopwords y stemming.
- Vectorización de texto utilizando TF-IDF.
- Implementación de dos modelos de clasificación: Regresión Logística y Random Forest.
- Evaluación detallada de modelos con métricas de precisión, recall y F1-score.
- Visualización de resultados mediante matrices de confusión.

## Dataset

El dataset utilizado en este proyecto se obtuvo mediante la versión gratuita de NewsAPI y está alojado en GitHub.

- **Fuente de datos**: NewsAPI (versión gratuita)
- **Ubicación del dataset**: [GitHub Repository](https://github.com/BeaEsparcia/Clasificacion_Noticias)

## Tecnologías utilizadas

- Python 3.7+
- Pandas: para manipulación de datos
- NLTK: para procesamiento de lenguaje natural
- Scikit-learn: para modelado y evalucación
- Seaborn y Matplotlib: para visualización de resultados

## Instalación y Uso

1. Clonar el repositorio
   git clone https://github.com/BeaEsparcia/Clasificacion_Noticias.git
cd Clasificacion_Noticias

3. Instalar las dependencias:
   pip install -r requirements.txt
   
4. Descargar recursos de NLTK:
   ```Python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')   
   
5. Ejecutar el notebook Jupyter Clasificacion_Noticias.ipynb


## Metodología

### Preprocesamiento de texto
1. Conversión a minúsculas
2. Eliminación de puntuación
3. Tokenización
4. Eliminación de stopwords en español
5. Stemming utilizando SnowballStemmer para español

### Vectorización
- Utilización de TF-IDF Vectorizer para convertir el texto en características numéricas

### Modelos de Clasificación
- **Regresión Logística**: un modelo lineal eficiente para problemas de clasificación.
- **Random Forest Classifier**: un modelo basado en árboles de decisión que mejora la precisión combinando múltiples árboles.

## Evaluación de los Modelos

Los modelos fueron evaluados utilizando las siguientes métricas:

- **Exactitud (Accuracy):** Mide el porcentaje de predicciones correctas sobre el total de predicciones.
- **Precision:** Mide la proporción de verdaderos positivos entre el total de positivos predichos.
- **Recall:** Mide la proporción de verdaderos positivos entre el total de positivos reales.
- **F1-Score:** Mide la armonía entre la precisión y el recall.
- **Matriz de Confusión:** Proporciona una visión detallada de las verdaderas positivas, falsas positivas, verdaderas negativas y falsas negativas para cada categoría.

## Resultados
### Regresión Logística:
- **Exactitud General:** 47%
- **Rendimiento por Categoría:**
  - **Cultura:** Precision: 0.36, Recall: 0.40, F1-Score: 0.38
  - **Deportes:** Precision: 0.59, Recall: 0.42, F1-Score: 0.49
  - **Economía:** Precision: 0.57, Recall: 0.58, F1-Score: 0.57
  - **España:** Precision: 0.47, Recall: 0.50, F1-Score: 0.48
  - **Internacional:** Precision: 0.51, Recall: 0.47, F1-Score: 0.49
  - **Sociedad:** Precision: 0.37, Recall: 0.42, F1-Score: 0.39
- **Promedio Macro:** Precision: 0.48, Recall: 0.47, F1-Score: 0.47
- **Promedio Ponderado:** Precision: 0.48, Recall: 0.47, F1-Score: 0.47

### Random Forest:
- **Exactitud General:** 42%
- **Rendimiento por Categoría:**
  - **Cultura:** Precision: 0.31, Recall: 0.42, F1-Score: 0.36
  - **Deportes:** Precision: 0.57, Recall: 0.44, F1-Score: 0.50
  - **Economía:** Precision: 0.57, Recall: 0.55, F1-Score: 0.56
  - **España:** Precision: 0.41, Recall: 0.39, F1-Score: 0.40
  - **Internacional:** Precision: 0.41, Recall: 0.37, F1-Score: 0.39
  - **Sociedad:** Precision: 0.33, Recall: 0.34, F1-Score: 0.34
- **Promedio Macro:** Precision: 0.43, Recall: 0.42, F1-Score: 0.42
- **Promedio Ponderado:** Precision: 0.43, Recall: 0.42, F1-Score: 0.42

Para ver resultados detallados por categoría, consulte la sección de "resultados" en el cuaderno.

## Conclusiones y áreas de mejora: 

El modelo de clasificación de noticias mostró un rendimiento aceptable, con margen de mejora. Algunas áreas potenciales para futuros desarrollos incluyen:

1. Ampliar el dataset con más fuentes de noticias
2. Experimentar con modelos más avanzados como redes neuronales
3. Realizar un análisis más profundo de las características importantes para la clasificación

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abra un issue primero para discutir qué le gustaría cambiar.

## Licencia

Este proyecto está bajo la Licencia MIT. Vea el archivo LICENSE para más detalles.

## Contacto

[Bea Esparcia] - [esparcia.beatriz@gmail.com] - [www.linkedin.com/in/beaesparcia]

   

  

