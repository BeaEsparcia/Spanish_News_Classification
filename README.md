# Proyecto de clasificación de noticias en español

## Descripción
Este proyecto utiliza técnicas de procesamiento de lenguaje natural (PLN) y aprendizaje automático para clasificar noticias en español en diferentes categorías.

## Dataset
El dataset utilizado en este proyecto se obtuvo mediante la versión gratuita de NewsAPI y está alojado en GitHub.

- **Fuente de datos**: NewsAPI (versión gratuita)
- **Ubicación del dataset**: [GitHub Repository](https://github.com/BeaEsparcia/Clasificacion_Noticias)

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
- Regresión Logística
- Random Forest Classifier

## Tecnologías Utilizadas
- Python
- Pandas: Para manipulación de datos
- NLTK: Para procesamiento de lenguaje natural
- Scikit-learn: Para modelado y evaluación
- Seaborn y Matplotlib: Para visualización de resultados

## Instalación y Uso
1. Clonar el repositorio
2. Instalar las dependencias:
   pip install nltk seaborn pandas scikit-learn matplotlib
3. Descargar recursos de NLTK:
   ```Python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')   
   
4. Ejecutar el notebook Jupyter

## Resultados
[Aquí puedes incluir un resumen de tus resultados, como la precisión de cada modelo]

## Desafíos y observaciones

## Áreas de Mejora
1. Ampliar el dataset con más fuentes de noticias
2. Experimentar con modelos más avanzados como redes neuronales
3. Realizar un análisis más profundo de las características importantes para la clasificación

## Contacto
[Bea Esparcia] - [esparcia.beatriz@gmail.com] 

   

  

