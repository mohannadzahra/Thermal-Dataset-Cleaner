# Thermal-Dataset-Cleaner

# Documentation: Thermal Dataset Cleaner

1. Introduction
   
The Thermal Dataset Cleaner is a Python-based tool developed to clean and correct thermal infrared (TIR) image datasets. It automatically identifies pixels with values outside a predefined valid thermal range and replaces them using the mean values of neighboring valid pixels.

The tool is designed to process multiple thermal TIFF images in a folder, identify their corresponding metadata CSV files, correct invalid pixel values, and save the processed images and metadata in a separate output directory.

The main objective is to improve the quality and consistency of thermal image datasets while preserving the original files.

2. Requirements and Libraries
   
The following Python libraries are required to execute the notebook:

Library	Purpose

NumPy	Numerical operations and image array manipulation
Matplotlib	Image visualization
GDAL	Reading and writing geospatial raster images
Rasterio	Reading and saving TIFF images
Pandas	Data handling
SciPy	Scientific image-processing operations
OS	Directory and file management
Glob	Searching for TIFF and CSV files
Shutil	Copying metadata files
Math	Mathematical operations

Install the required libraries using:
