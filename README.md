# LandSurfaceTemperature (LST)

## Introduction
This repository shows how to calculate Land Surface Temperature from NASA Tutorial using Landsat 8 images (https://giscrack.com/how-to-calculate-land-surface-temperature-with-landsat-8-images/). 


## Technologies
* Python3 (tiffile, numpy, rasterio, shapely, geopandas, fiona, pycrs, json, scipy, os, sys, pprint, gdal, imagecodecs)
* Anaconda/Miniconda3
* ipynb platform

## Scripts
* functions.ipynb - includes each function used for calculating LandSurfaceTemperature
* clip_data.ipynb - fuction for clipiing raster data
* LST_calcaulation.ipynb - the main scrip containing file structure and dictionaries, calling fuctions

## To run this project
* Install Python3 from https://www.python.org/downloads/
* Install Conda3 for Python 3 from https://docs.conda.io/en/latest/miniconda.html
* Setup a kernel for Jupyter Lab from https://jupyter-client.readthedocs.io/en/stable/kernels.html
* Setup a Conda environment from https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html
* In LST_calculation.ipynb set up input and output folder
* Run LST_calculation.ipynb
