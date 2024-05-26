# Spectral Data Mapping

## Overview
Spectral Data Mapping is a Python tool designed to convert numerical data into vibrant visual representations using a spectrum of colors. This project provides a straightforward solution for visualizing numeric datasets, enhancing data comprehension and analysis through intuitive color mapping.

## Project Details
Spectral Data Mapping utilizes the powerful capabilities of NumPy and Matplotlib libraries to transform numerical data into RGB images. The core functionality includes data normalization, automatic calculation of image dimensions, and color mapping for both positive and negative values. By leveraging these features, users can effortlessly generate visually appealing representations of their data, facilitating better insights and understanding.

## Features
Spectral Data Mapping offers the following key features:

### 1. Numeric Data to Colorful Images Conversion
Converts numerical data arrays into visually stunning RGB images, enabling users to visualize complex datasets in a simplified and intuitive manner.

### 2. Data Normalization
Provides a function to normalize input data, ensuring optimal visualization by scaling data values to fit within the RGB color space.

### 3. Automatic Image Dimension Calculation
Automatically calculates the dimensions of the output image based on the length of the input data array, eliminating the need for manual specification.

### 4. Intuitive Color Mapping
Maps data values to colors in a spectrum, with distinct representations for positive and negative values. This intuitive color mapping enhances the interpretability of the generated images.

## Usage
To use Spectral Data Mapping, follow these simple steps:

1. **Import Libraries**: Begin by importing the required libraries, NumPy and Matplotlib.
   
   ```python
   import numpy as np
   import matplotlib.pyplot as plt
2. **Define Data**: Define your numerical data array that you want to visualize.
   
   ```python
   data = [-15, -14, -13, -12, -11, -10, -9, -8, -7, -6, -5, -4, -3, -2, -1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]
3. **Generate Image**: Use the `display_image_from_colors` function to generate and display the RGB image representing the data.
   
   ```python
   display_image_from_colors(data, axis='off')

## Example
Consider the following example demonstrating the usage of Spectral Data Mapping:

In this example, the provided numerical data array is converted into an RGB image using Spectral Data Mapping. The resulting image visually represents the data distribution, with distinct colors assigned to different data values.


## Conclusion
Spectral Data Mapping is a versatile tool for data visualization, offering a simple yet powerful solution for converting numerical data into colorful images. By leveraging the capabilities of NumPy and Matplotlib, users can easily explore and interpret their datasets in a visually engaging manner. Whether analyzing trends, patterns, or anomalies, Spectral Data Mapping empowers users to gain valuable insights from their data through vibrant visual representations.
  
