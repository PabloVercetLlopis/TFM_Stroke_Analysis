# Análisis Predictivo de Ictus mediante Machine Learning

Este repositorio contiene el trabajo de fin de máster (TFM) titulado: **"Accidente Cerebrovascular: Análisis Estadístico de los Factores de Riesgo y Creación de Modelos Predictivos mediante Machine Learning"**. En este proyecto se evaluaron diversos algoritmos de Machine Learning para predecir el riesgo de sufrir un ictus basándose en datos clínicos.

## Descripción del Proyecto
El accidente cerebrovascular (ACV) es una de las principales causas de discapacidad y mortalidad. Este TFM utiliza herramientas estadísticas y de aprendizaje automático para:
- Identificar factores de riesgo asociados al ictus.
- Desarrollar y evaluar modelos predictivos (Random Forest, Support Vector Machine y Naive Bayes).
- Comparar los resultados obtenidos con investigaciones previas.

## Estructura del Repositorio
- **`Archivos/`**: Documento completo del TFM en formato PDF y reproducible en RMarkdown.
- **`Datos/`**: Contiene los datos utilizados, incluyendo el archivo original (`stroke.csv`).
- **`Resultados/`**: Resultados en forma de gráficos y tablas, incluyendo métricas y visualizaciones de los modelos.
- **`Sources/`**: Código fuente organizado por etapas:
  - Análisis exploratorio y visualizaciones.
  - Preprocesamiento de datos.
  - Evaluación de los modelos utilizados.
  - Código del modelo Naive Bayes.
  - Código del modelo Random Forest
  - Código del modelo SVM
- **`Licencia`**: Licencia del proyecto.  
- **`README.md`**: Introducción y guía del proyecto.

## Tecnologías Utilizadas
- **Lenguaje**: R
- **Paquetes principales**: `tidymodels`, `caret`, `ggplot2`, `survival`, `kableExtra`
- **Datos**: Dataset público de [Kaggle](https://www.kaggle.com/).

## Cómo Reproducir el Proyecto
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/TFM_Stroke_Analysis.git
   cd TFM_Stroke_Analysis
2. Instala las dependencias necesarias en R:
install.packages(c("tidymodels", "caret", "ggplot2", "kableExtra", "randomForest", "e1071", "xgboost"))

3.Ejecuta los scripts en el directorio src/ según las etapas:
    Preprocesamiento: data_preprocessing.R
    Análisis exploratorio: exploratory_analysis.R
    Modelos predictivos: src/models/*.R
    Evaluación de modelos: evaluation.R
    Consulta los resultados en la carpeta results/.

## Resultados Principales
Modelo con mejor rendimiento: Support Vector Machine (SVM)
Sensibilidad: 0.82
Especificidad: 0.71
AUC: 0.76
Los modelos SVM y Random Forest demostraron ser las mejores opciones para predecir ictus en base a este dataset.

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
