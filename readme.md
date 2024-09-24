# Machine Learning Project Pipeline

Este proyecto está diseñado para desarrollar un pipeline de machine learning completo, desde la gestión y preprocesamiento de datos hasta el entrenamiento, evaluación de modelos y visualización de resultados.

## Estructura del Proyecto

├── .gitignore  
├── data  
│   ├── external  
│   ├── processed  
│   ├── raw  
├── main.py  
├── notebooks  
├── README.md  
├── requirements.txt  
├── src  
│   ├── data  
│   ├── features  
│   ├── models  
│   ├── utils  
│   ├── visualization  
├── tests

## Descripción de las Carpetas y Archivos:

- **.gitignore**: Archivo que especifica qué archivos y directorios deben ser ignorados por Git.
  
- **data**: Contiene los datos usados en el proyecto.
  - **external**: Datos obtenidos de fuentes externas que no han sido procesados.
  - **processed**: Datos que han sido preprocesados y están listos para ser usados en el entrenamiento de los modelos.
  - **raw**: Datos sin procesar en su formato original.
  
- **main.py**: Archivo principal que orquesta la ejecución del pipeline completo.

- **notebooks**: Este directorio está destinado a notebooks Jupyter, útiles para realizar análisis exploratorios, pruebas y documentación adicional.

- **requirements.txt**: Archivo con las dependencias del proyecto que deben ser instaladas para ejecutarlo.

- **src**: Código fuente del proyecto, estructurado de la siguiente manera:
  - **data**: Contiene scripts para cargar y preprocesar los datos.
    - `load_data.py`: Funciones para cargar los datos desde distintas fuentes.
    - `preprocess.py`: Funciones para limpiar y preprocesar los datos.
  
  - **features**: Contiene scripts para generar nuevas características a partir de los datos.
    - `build_features.py`: Funciones para crear y transformar las características.

  - **models**: Scripts para entrenar y evaluar los modelos de machine learning.
    - `train_model.py`: Script para el entrenamiento de modelos.
    - `evaluate_model.py`: Funciones para evaluar el rendimiento del modelo usando distintas métricas.

  - **utils**: Utilidades y funciones de apoyo.
    - `helper_functions.py`: Funciones auxiliares reutilizables a lo largo del proyecto.

  - **visualization**: Contiene scripts para visualizar los datos y los resultados del modelo.
    - `visualize.py`: Funciones para crear gráficos y visualizaciones útiles.

- **tests**: Contiene los tests para asegurar que las funciones y el pipeline funcionen correctamente.

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```

2. Instalar las dependencias:

    ```bash
    pip install -r requirements.txt
    ```

3. Ejecutar el pipeline principal:

    ```bash
    python main.py
    ```

## Licencia

Este proyecto está licenciado bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para más información, contacta a: [lbustio@gmail.com](mailto:lbustio@gmail.com)