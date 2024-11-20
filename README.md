Este repositorio presenta un análisis detallado sobre el mercado de conectividad a Internet en Argentina, con el objetivo de identificar tendencias y oportunidades en el uso de diversas tecnologías, velocidades de conexión y cobertura. El proyecto incluye procesos de ETL (Extracción, Transformación y Carga de datos), un Análisis Exploratorio de Datos (EDA) para una comprensión profunda del conjunto de datos, y un dashboard interactivo en formato .PBIX con KPIs medibles y filtros según las necesidades del usuario.

## Instalación y Requisitos

1. Clona el repositorio.
2. Accede al directorio del proyecto.
3. Crea un entorno virtual.
4. Activa el entorno virtual.
5. Instala las dependencias ejecutando el siguiente comando:

   ```bash
   pip install -r requirements.txt


## Estructura del Proyecto

La estructura del proyecto está organizada de la siguiente manera:

- **data/**: Contiene los archivos de datos en formato CSV, utilizados en el análisis y organizados por página.
- **KPI/**: Se encuentran algunas tablas modificadas
- **notebooks/**: Incluye los notebooks Jupyter donde se lleva a cabo el proceso de **ETL** y el análisis exploratorio de datos (**EDA**), esenciales para cada página.
  - **ETL/**: Realiza la transformación y limpieza de los datos, así como la separación por páginas, para su almacenamiento en la carpeta **data**.
  - **EDA/**: Ejecuta el análisis exploratorio de los datos con el fin de extraer información relevante.
- **dashboard/**: Almacena el archivo visual de Power BI, que incluye los KPIs y el análisis realizados.
- **requirements.txt**: Contiene las dependencias necesarias para ejecutar el proceso de **ETL** y **EDA**.
- **README.md**: Proporciona la documentación detallada del análisis, incluidas las conclusiones y la metodología utilizada.

## Datos y Fuentes

- **ENACOM Internet**: El **Ente Nacional de Comunicaciones (ENACOM)** es la autoridad reguladora de las telecomunicaciones en Argentina. Su misión es establecer políticas públicas en telecomunicaciones y radiodifusión, supervisando y regulando los servicios de internet, telefonía fija y móvil, y radiodifusión.
