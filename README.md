# Enriquecimiento de Datos de Fitoplancton mediante Web Scraping

Este proyecto se enfoca en la creación de un conjunto de datos enriquecido de imágenes de fitoplancton mediante la recopilación automatizada de datos desde dos fuentes especializadas: **MVCO Dashboard Dataset** y **PlanktonNet Dataset**. Se implementaron técnicas avanzadas de **web scraping** utilizando **Selenium** y **Google Colab**, logrando recolectar, organizar y categorizar miles de imágenes con información taxonómica detallada.

## MVCO Dashboard Dataset

- **Fuente:** Martha’s Village Coast Observatory (MVCO) a través de la plataforma IFCB Dashboard del WHOI.
- **Proceso:**
  1. Se desarrolló un bot en **Selenium** para descargar imágenes y archivos de clasificación ("Autoclass") desde el periodo **octubre 2019 a diciembre 2019**.
  2. El archivo "Autoclass" contenía las clasificaciones de 103 categorías, asignadas con un porcentaje de similitud por un modelo del centro de investigación.
  3. Las imágenes descargadas se organizaron automáticamente en carpetas basadas en la clasificación con mayor porcentaje de similitud.
- **Resultado:**
  - Más de **10,000 imágenes** clasificadas en 103 categorías, listas para análisis y entrenamiento de modelos de aprendizaje automático.

![image](https://github.com/user-attachments/assets/6c8ad9ce-d6f5-416a-aef3-115f47056f77)


## PlanktonNet Dataset

- **Fuente:** Proveedor de Datos PlanktonNet del Instituto Alfred Wegener para la Investigación Polar y Marina.
- **Proceso:**
  1. Se creó un bot en **Selenium** para buscar imágenes relacionadas con una lista de 72 géneros de fitoplancton.
  2. Las imágenes fueron descargadas y organizadas en carpetas específicas por género.
- **Resultado:**
  - Recolección de más de **3,000 imágenes** distribuidas en 72 géneros, enriqueciendo la diversidad del conjunto de datos.
![image](https://github.com/user-attachments/assets/f9b42524-e8fa-4704-a6b3-c8c43b266fa3)


## Tecnologías Utilizadas

- **Librerías y herramientas:** Selenium, Google Colab, Python.
- **Técnicas de manejo de datos:** Concatenación y organización automática de archivos CSV, categorización de imágenes en carpetas específicas.

---

