# Análisis de NLP: Corpus Literario - Poemas Storni - Pizarnik

## Descripción
El corpus seleccionado está compuesto por poemas de Alfonsina Storni y Alejandra Pizarnik, dos de las voces más influyentes de la poesía argentina del siglo XX. Los textos abordan temáticas recurrentes como el amor, el dolor, la muerte, el cuerpo, el silencio y el infinito, con estilos particulares que reflejan la sensibilidad y el contexto de cada autora. Mientras Storni combina fuerza expresiva con un lirismo vinculado a lo social y lo íntimo, Pizarnik despliega una escritura más introspectiva, cargada de símbolos oscuros y existenciales.

El objetivo del análisis es explorar similitudes y diferencias estilísticas y temáticas entre ambas poetas, utilizando herramientas de procesamiento de lenguaje natural (PLN). A través de técnicas como TF-IDF, embeddings y análisis semántico, se busca detectar patrones de vocabulario, identificar relaciones entre poemas y observar cómo se organizan las afinidades y distancias dentro del corpus.

De este modo, el estudio no solo permite comprender mejor la obra de cada autora, sino también reflexionar sobre el aporte que ofrecen los métodos computacionales para el análisis literario. La combinación de estadística, modelos lingüísticos y poesía revela nuevas formas de leer y comparar textos, ampliando la interpretación crítica tradicional.

## Información del Corpus
- **Tipo**: Literatura
- **Tamaño**: 30 textos, aproximadamente 4900 palabras totales
- **Fuentes principales**: CiudadSeva.com, Poemasdelalma.com, Poesi.as
- **Período temporal**: 1916 a 1962 (Siglo XX)
- **Criterios de selección**: Reune una selección de poemas de dos autoras argentinas reconocidas con obras publicadas durante el siglo XX. Storni de comienzos de siglo y Pizarnik algunas decadas más adelante. Esto permite una selección de varios extractos o poemas completos y un analisis sobre diferencias estilísticas de cada una.

## Técnicas de NLP Aplicadas
- Preprocesamiento de texto (limpieza, tokenización, stop words)
- Análisis con Bag of Words (BoW) y TF-IDF
- Análisis con Word Embeddings (spaCy)
- Análisis con POS

## Principales Hallazgos
- Descubrimos patrones claros de vocabulario y estilo entre Alfonsina Storni y Alejandra Pizarnik.
- Cada autora tiene términos característicos y uso de POS distintivos que permiten una buena diferenciación entre sí.
- Evidenciamos cómo los embeddings capturan similitud semántica entre poemas que no comparten muchas palabras exactas.
- Para este corpus poético, los embeddings fueron superiores para el análisis de semántica, mientras que TF-IDF/BoW fue útil para analizar frecuencia y armar ranking de términos.

## Tecnologías Utilizadas
- **Lenguaje**: Python 3.x  
- **Procesamiento y análisis de datos**:  
  - pandas  
  - numpy  
- **Procesamiento de lenguaje natural (NLP)**:  
  - spaCy  
  - nltk  
- **Machine Learning / Análisis**:  
  - scikit-learn  
- **Visualización de datos**:  
  - matplotlib  
  - seaborn  
  - matplotlib-venn  
  - wordcloud  
- **Utilidades**:  
  - os (manejo de archivos y directorios)  
  - re (expresiones regulares)  
  - string (utilidades de texto)  
  - collections.Counter (conteo eficiente de elementos)  
  - pickle (serialización de objetos)  


## Instrucciones de Reproducción
1. Clonar este repositorio
2. Instalar dependencias: `pip install -r requirements.txt`
3. Ejecutar el notebook: `jupyter notebook notebooks/analisis_integrador.ipynb`

## Limitaciones y Trabajo Futuro

### Limitaciones
- El análisis de sentimiento no fue confiable por el lenguaje poético y simbólico.  
- No se capturaron metáforas, simbolismos ni estructura poética específica (estrofas, rimas).  
- Algunas palabras importantes pueden haber sido eliminadas al aplicar stopwords o lematización.  

### Trabajo Futuro
- Identificación automática de estilos literarios y comparación entre autores.  
- Filtrado o recomendación de poemas por similitud semántica.  
- Base para estudios de lingüística computacional o análisis literario cuantitativo.  


## Autor
Tamara Peña - [GitHub](https://github.com/Tamara-WJP) 
Trabajo Integrador - NLP - 09/2025