# s19-01-m-data-bi
#                                Analisis de afiliados activos en el Seguro Integral de Salud (SIS) con diagnóstico de Diabetes Mellitus

# <h1 align="center"> HealthScope Analytics </h1>

<p align=center>
 <img width="" height="500" src="https://imgur.com/ohe5XCS.jpg" alt="logo empresa">
<p/>

## Índice

1. [Descripción del proyecto](#Descripción-del-proyecto)
2. [MVP](#MVP)
3. [Alcance del MVP](#Alcance-del-MVP)
4. [Stack de tecnologías y herramientas](#Stack-de-tecnologías-y-herramientas)
5. [Metodología de gestión de proyectos](#Metodología-de-gestión-de-proyectos)
6. [Etapas del proyecto](#Etapas-del-proyecto)
7. [Contenido del proyecto](#Contenido-del-proyecto)
8. [Integrantes del equipo](#Integrantes-del-equipo)


## Descripción del proyecto

Este proyecto utiliza información publicada que proporciona información nominal de los afiliados activos al Seguro Integral de Salud (SIS) que tienen al menos un diagnóstico definitivo de Diabetes Mellitus (DM). Se incluye también información respecto de si ha recibido atenciones en los últimos tres meses según la fecha de corte de los afiliados activos.
La granularidad de esta información está al nivel de afiliado, cada registro representa un afiliado activo al SIS con diagnóstico de Diabetes Mellitus. La evaluación para determinar si un afiliado ha tenido un diagnóstico de DM se ha realizado sobre las atenciones desde el año 2018 a la fecha de corte considerando los diagnósticos definitivos.
Este proyecto busca, utilizando la ciencia de datos, identificar características que sean influyentes y puedan minorizar los gastos de hospitalizaciones en pacientes con DM, revisando cómo optimizar el servicio existente.

# MVP 

## Alcance del proyecto

El presente proyecto trata de resolver los siguientes problemas:

  📌 **Gestión de la salud de pacientes diabéticos** para identificar patrones de comorbilidades como obesidad, hipertensión o problemas de salud mental; analizar el impacto de estas comorbilidades en el uso de servicios de salud.
  
  📌 **Optimización de recursos en el sistema de salud** para determinar los costos asociados a la atención de pacientes diabéticos y sus hospitalizaciones; evaluar si ciertos perfiles de pacientes (edad, grupo etario,sexo, ubicación) requieren más recursos o tienen más hospitalizaciones.
  
  📌 **Disparidades geográficas y demográficas** para detectar diferencias en la calidad o frecuencia de atención según departamento o provincia; identificar grupos demográficos (edad, sexo) con mayor riesgo o menos acceso a servicios.
  
  📌 **Evaluación de la carga de la enfermedad en el sistema** para analizar la frecuencia de hospitalizaciones y días de hospitalización para entender la gravedad promedio de los casos; medir el impacto económico de la diabetes mellitus en el sistema de salud.

## Stack de tecnologías y herramientas

|  Librería/herramienta    |   Logo                                    | Descripción                                                                                                           |
|----------------------|-----------------------------------------|----------------------------------------------|
| **Pandas**   |      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/1200px-Pandas_logo.svg.png" width="100">   | Librería de Python para manipulación y análisis de datos.|
|**Matplotlib**|<img src="https://matplotlib.org/_static/logo_light.svg" width="100">| Librería usada para la generación de gráficos en dos dimensiones.|
|**Seaborn**|<img src="https://seaborn.pydata.org/_images/logo-tall-lightbg.svg" width="100"> | Librería de Python creada sobre matplotlib, usada para crear gráficos estadísticos.|
| **Jupyter**|<img src="https://jupyter.org/assets/homepage/main-logo.svg" width="65">| Software gratuito, estándares abiertos y servicios web para informática interactiva en todos los lenguajes de programación.|
| **Visual Studio Code**|<img src="https://static-00.iconduck.com/assets.00/visual-studio-code-icon-512x506-2fdb6ar6.png" width="70">| Editor de código fuente.|
| **Colaboratory con Python**|<img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="60">| Plataforma de Google basada en Jupyter Notebooks, junto con las librerías de Python para análisis de datos como Pandas y Matplotlib.|
| **Power BI**|<img src="https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/Analysts_PBI?resMode=sharp2&op_usm=1.5,0.65,15,0&wid=2000&qlt=99&fmt=png-alpha&fit=constrain" width="100">| Herramienta líder en el mercado para crear visualizaciones de datos avanzadas, informes interactivos y paneles de control.|
| **Canva**|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bb/Canva_Logo.svg/250px-Canva_Logo.svg.png" width="100">| Plataforma de diseño gráfico y composición de imágenes.|
| **Power Point**|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/16/Microsoft_PowerPoint_2013-2019_logo.svg/610px-Microsoft_PowerPoint_2013-2019_logo.svg.png" width="100">| Microsoft PowerPoint (PPT) es un software de ofimática diseñado para realizar presentación de diapositivas.|
| **Python**|<img src="https://seeklogo.com/images/P/python-logo-A32636CAA3-seeklogo.com.png" width="50">| Lenguaje de programación utilizado para análisis de datos y desarrollo de aplicaciones.|
| **GitHub**|<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" width="100">| Plataforma de desarrollo colaborativo para proyectos de software.|
| **Draw.io**|<img src="https://store-images.s-microsoft.com/image/apps.14142.2ec57164-ba5b-42ee-8253-ade72ca74c8d.e8efbcc8-e27f-4682-9321-eb111eb3bc68.950e1c22-0dd9-4079-807b-145ecdb6df9c.png" width="100">| Software de diagramas en línea gratuito para crear diagramas de flujo, diagramas de procesos, organigramas, UML, ER y diagramas de red.|
| **Google Drive**|<img src="https://upload.wikimedia.org/wikipedia/commons/1/12/Google_Drive_icon_%282020%29.svg" width="100"> | Servicio de alojamiento y sincronización de archivos.|
| **Streamlit** | <img src="https://streamlit.io/images/brand/streamlit-logo-primary-colormark-darktext.png" width="100"> | Streamlit es una herramienta de código abierto diseñada para crear aplicaciones web interactivas y visualizaciones de datos de manera rápida y sencilla utilizando Python.|

## Metodología de gestión de proyectos 

➡️ Para gestionar este proyecto utilizamos **Kanban**, un método de gestión de proyectos que ayuda a los equipos a visualizar su trabajo, mejorar la eficiencia y encontrar un equilibrio entre las tareas y la disponibilidad de los miembros. 

➡️ Asimismo, implementamos un **Brief**, un documento que establece los objetivos y la dirección de un proyecto, y que guía a los miembros del equipo para que trabajen de manera eficiente.

➡️ Para la gestión, organizamos las fases del proyecto en cuatro **sprints semanales**.

➡️ También utilizamos **Google Meet** para las daily meeting y las reuniones con el Team Leader, como así también **Slack** y **WhatsApp** para la comunicación diaria entre los miembros del equipo.

## Etapas del proyecto

### 1) **Problemas, preguntas y recolección de datos:** 

### 2) **Limpieza de datos:**
Se realizó una limpieza del dataset con Power Query; también se creó el diagrama entidad relación dentro de Power BI, tomando como referencia un diseño previo hecho en Draw.io.

### 3) **Análisis exploratorio de datos:** 
Se realizó un Análisis Univariado: se analizaron las distribuciones de las variables numéricas y categóricas, incluyendo la edad, el valor neto y el valor neto hospitalario, se encontraron distribuciones sesgadas y con outliers en algunas variables, lo que sugiere la necesidad de transformaciones o eliminación de outliers.

En el Análisis Bivariado: se analizaron las relaciones entre las variables numéricas y categóricas, incluyendo la relación entre el valor neto hospitalario y el sexo, se crearon gráficos de barras apiladas y histogramas para visualizar las relaciones entre las variables.

En el Análisis Multivariado: se creó un gráfico de pares (pair plot) para visualizar las relaciones entre las variables numéricas, se encontraron relaciones complejas entre las variables, lo que sugiere la necesidad de un modelo que pueda capturar estas interacciones.

### 4) **Visualización:** 
Primeramente se realizó un mockup en Canva para establecer una idea y criterio general acerca de la creación de los gráficos y la disposición de los mismos en el tablero. Luego, se crearon las visualizaciones en Power BI.

### 6) **Entrenamiento y Evaluación del Modelo Predictivo:**
Desarrollamos un modelo predictivo del riesgo de hospitalización mediante aprendizaje automático, centrándonos en la selección de características, el equilibrio de datos y el escalamiento robusto.

Probamos varios clasificadores y XGBoost superó a otros después de la optimización mediante RandomizedSearchCV.

El modelo XGBoost final logró una puntuación ROC AUC casi perfecta de 0,992 y una precisión del 100 % en el conjunto de prueba.

La validación cruzada garantizó la generalización del modelo y se siguieron las mejores prácticas para la reproducibilidad y el rendimiento.


### 6) **Presentación:**
Finalmente, se presentó el MVP en el Demo Day del día 12/12/2024 utilizando PowerPoint para la presentación del tablero y haciendo una demostración en vivo del deploy, utilizando Streamlit.

## Contenido del proyecto 

- 📊 **Dashboard:** Visualización interactiva de los datos en Power BI. [Dashboard](./Dashboard)
- 🤖 **Deploy:** Modelo de Machine Learning. [Deploy](https://hospitalizado-diabetes.streamlit.app/)
- 📂 **Datasets:** Acceso al dataset utilizado para el MVP. Enlace al dataset. [Datasets](./Dataset)
- 📑 **Presentación:** Presentación del proyecto en PowerPoint. Enlace a la presentación. [Presentación](./Presentación)

## Integrantes del equipo.

|                         | Nombre   |   Rol                    | GitHub & LinkedIn                                                                                                                                                                                          |
| ----------------------------- | -------- | ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="60" height="60" src="https://github.com/Sergius-DS.png" alt="Sergius-DS" /> | Sergio Rivera Bustamante | Data Scientist | [![Github](https://skillicons.dev/icons?i=github)](https://github.com/Sergius-DS) [![Linkedin](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/sergio-rivera-bustamante-6642b836/)                         |
|                               |
| <img width="60" height="60" src="" alt="Nombre" /> | Juan Campos | Data Scientist |  [![Github](https://skillicons.dev/icons?i=github)](https://github.com/Sergius-DS) [![Linkedin](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/sergio-rivera-bustamante-6642b836/)                         |  
|                               |
| <img width="60" height="60" src="" alt="Nombre" /> | Raúl Almao | Data Scientist |  [![Github](https://skillicons.dev/icons?i=github)](https://github.com/Sergius-DS) [![Linkedin](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/sergio-rivera-bustamante-6642b836/)                         |
|                               |
| <img width="60" height="60" src="" alt="Nombre" /> | Arelys Acevedo | Data Analyst |  [![Github](https://skillicons.dev/icons?i=github)](https://github.com/Sergius-DS) [![Linkedin](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/sergio-rivera-bustamante-6642b836/)                         |
|                               |
| <img width="60" height="60" src="https://github.com/Mathiroldan.png" alt="Mathiroldan" /> | Mathias Roldán | Data Analyst |  [![Github](https://skillicons.dev/icons?i=github)](https://github.com/Mathiroldan) [![Linkedin](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/mathias-roldan)                         |
|                               |
| <img width="60" height="60" src="https://avatars.githubusercontent.com/u/132181881?v=4" alt="augustogh29" /> | Augusto García | Data Analyst |  [![Github](https://skillicons.dev/icons?i=github)](https://github.com/augustogh29) [![Linkedin](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/augusto-garcia-a03737234/)                         |
|                               |
