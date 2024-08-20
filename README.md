## Project Overview 

This repository contains Jupyter notebooks for processing, analysing, and visualising signal data. The main project code involves the following key components:

**Data Preprocessing**: Loading and preparing signal data from .mat files.   
**Signal Processing**: Applying wavelet decomposition, thresholding, and reconstruction of signals.   
**Peak Detection**: Identifying peaks and troughs in signals.   
**Event Isolation**: Extracting segments of signals based on detected peaks.   
**Visualisation**: Generating plots to justify parameter choices and analyse results.   
**Model Building**: Creating and compiling a Convolutional Neural Network (CNN) for signal classification.   

Requirements:
- Python 3.x   
- numpy   
- scipy   
- pywt (PyWavelets)   
- matplotlib   
- tensorflow (for CNN model)   

You can install the necessary packages using pip: pip install numpy scipy pywt matplotlib tensorflow

The dataset used in this project is stored in .mat format and includes multiple signal records. For access to the dataset or any data-related inquiries, please contact:

Joshua Edel: joshua.edel@imperial.ac.uk

Alex Ivanov: alex.ivanov@imperial.ac.uk

This project is licensed under the MIT License and a part of Imperial College London.
