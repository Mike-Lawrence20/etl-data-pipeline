# ETL Data Pipeline Project

Este repositorio contiene el flujo de trabajo de un **ETL (Extract, Transform, Load)** realizado para un conjunto de datos, donde se procesan datos desde su estado crudo hasta una versión limpia y lista para análisis.

## Descripción

El proyecto implementa un pipeline de datos en Python que sigue el proceso de **extracción**, **transformación** y **carga** de los datos desde un archivo en formato `.xls` hasta un archivo `.csv` limpio y listo para análisis. Este pipeline también incluye los resultados de la transformación de datos, que están disponibles para su revisión.

## Objetivos

- Extraer datos desde una fuente en formato `.xls`.
- Limpiar y transformar los datos utilizando diversas técnicas de preprocesamiento.
- Cargar los datos transformados en un archivo `.csv` para análisis posterior.
- Presentar los resultados finales en un Jupyter Notebook.

## Estructura del Repositorio

Este repositorio contiene los siguientes archivos:

- `etl_pipeline.ipynb`: El **Jupyter Notebook** con el código fuente y los pasos del proceso ETL.
- `data/`: Carpeta que contiene los archivos de datos utilizados en el proyecto.
  - `original_data.xls`: El archivo de datos original.
  - `cleaned_data.csv`: El archivo con los datos transformados y limpios.
- `results/`: Carpeta que contiene los resultados del pipeline y análisis finales.

## Requisitos

Para ejecutar el pipeline, es necesario tener instaladas las siguientes librerías:

- `pandas`
- `numpy`
- `openpyxl`
- `matplotlib`
- `seaborn`
