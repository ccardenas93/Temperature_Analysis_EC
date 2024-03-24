
# Análisis de Temperatura Regional

## Descripción
Este proyecto analiza las variaciones de temperatura en diferentes regiones, utilizando imágenes de ERA5-Land en formato TIFF. Convierte las temperaturas de Kelvin a Celsius, genera visualizaciones de mapas de calor georreferenciados, y produce GIFs que muestran la evolución de las temperaturas a lo largo del tiempo. Además, realiza un análisis de regresión para identificar tendencias en los datos.

## Requisitos
- Python 3
- Bibliotecas requeridas: os, glob, rasterio, numpy, imageio, matplotlib, cartopy, pandas, scipy, PIL

## Instalación
Primero, asegúrate de tener Python 3 instalado en tu sistema. Luego, instala las dependencias necesarias utilizando pip:

```
pip install numpy pandas matplotlib scipy rasterio cartopy imageio PIL
```

## Uso
El proyecto está estructurado en un Jupyter Notebook que incluye varios bloques de código destinados a procesar y visualizar datos de temperatura. Los pasos generales son:

1. Convertir los datos de temperatura de Kelvin a Celsius.
2. Generar mapas de calor para regiones específicas y visualizar la temperatura promedio anual.
3. Crear series temporales de las temperaturas promedio.
4. Fusionar imágenes de mapas y series temporales en una visualización compuesta.
5. Realizar un análisis de regresión lineal para evaluar las tendencias de temperatura.

Para ejecutar el notebook, abre una terminal, navega hasta el directorio que contiene el notebook y ejecuta:

```
jupyter notebook
```

## Contribución
Si deseas contribuir a este proyecto, por favor considera:

- Crear un fork del repositorio.
- Realizar tus cambios en una rama nueva.
- Enviar un pull request con tus cambios.

## Acknowledgments

- Gracias a los proveedores de los datasets de temperatura

---


# Regional Temperature Analysis

## Description
This project analyzes temperature variations across different regions using ERA5-Land data in TIFF format. It converts temperatures from Kelvin to Celsius, generates georeferenced heat maps, and produces GIFs showing the evolution of temperatures over time. Furthermore, it performs a regression analysis to identify trends in the data.

## Requirements
- Python 3
- Required libraries: os, glob, rasterio, numpy, imageio, matplotlib, cartopy, pandas, scipy, PIL

## Installation
First, ensure Python 3 is installed on your system. Then, install the necessary dependencies using pip:

```
pip install numpy pandas matplotlib scipy rasterio cartopy imageio PIL
```

## Usage
The project is structured in a Jupyter Notebook that includes various code blocks designed to process and visualize temperature data. The general steps are:

1. Convert temperature data from Kelvin to Celsius.
2. Generate heat maps for specific regions and visualize average annual temperature.
3. Create time series of average temperatures.
4. Merge map and time series images into a composite visualization.
5. Perform a linear regression analysis to assess temperature trends.

To run the notebook, open a terminal, navigate to the directory containing the notebook, and execute:

```
jupyter notebook
```

## Contribution
If you wish to contribute to this project, please consider:

- Forking the repository.
- Making your changes in a new branch.
- Submitting a pull request with your changes.

## Acknowledgments

- Thanks to the providers of the temperature datasets.
