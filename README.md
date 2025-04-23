# Proyecto ML-CRISPDM

Este es un proyecto realizado como parte de mis estudios en **Duoc UC**. El objetivo del proyecto fue aplicar la metodología **CRISP-DM** (Cross-Industry Standard Process for Data Mining) para trabajar con un conjunto de datos meteorológicos de Australia.

El flujo de trabajo cubre todo el proceso de minería de datos, desde la carga y limpieza de los datos, hasta la preparación para el modelado, siguiendo los pasos establecidos por CRISP-DM.

## Metodología CRISP-DM

El proyecto sigue los seis pasos de la metodología **CRISP-DM**, pero se detiene antes de la parte de modelado, específicamente en la preparación de los datos. Los pasos seguidos son:

1. **Comprensión del negocio**: Entender el objetivo del análisis de datos meteorológicos.
2. **Comprensión de los datos**: Cargar y explorar la base de datos de datos meteorológicos de Australia.
3. **Preparación de los datos**: Limpieza y transformación de los datos para hacerlos adecuados para el análisis.
4. **Modelado**: Aunque se ha llegado hasta la preparación de los datos, se contempla que el siguiente paso sería construir modelos predictivos.

## Descripción del proyecto

Este proyecto utiliza datos meteorológicos de Australia. La base de datos contiene información sobre diversas variables climáticas, y el objetivo principal es procesar y limpiar los datos para su análisis posterior.

### Objetivos

- **Cargar y explorar los datos**: Entender qué tipo de información contiene la base de datos.
- **Limpiar los datos**: Eliminar valores nulos, corregir inconsistencias y transformar variables para asegurar que los datos sean útiles.
- **Aplicar la metodología CRISP-DM**: Seguir los pasos de la metodología de minería de datos hasta la fase de preparación de datos.

## Estructura del proyecto

El proyecto está compuesto por un archivo Jupyter Notebook llamado **`ML-CrispDM.ipynb`**, donde se desarrolla todo el trabajo de carga, limpieza y análisis de los datos.

- **`ML-CrispDM.ipynb`**: Este archivo contiene todo el proceso de trabajo, desde la carga de los datos hasta la limpieza y preparación para el modelado.
- **`data/`**: Contiene los archivos de datos originales (puedes agregar esta carpeta si tu proyecto tiene datos).

## Requisitos

Para ejecutar el proyecto, asegúrate de tener instalado Python y las siguientes librerías:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
