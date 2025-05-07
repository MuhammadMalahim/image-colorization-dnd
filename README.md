# Image Colorization

This repository contains an image colorization project where a grayscale image is converted into a full-color image using machine learning techniques. The goal is to build and compare two models—a convolutional neural network (CNN) and a linear regression model—for this image-to-image translation task.

## Project Overview

The notebook walks through:

- Task overview and problem definition  
- Dataset loading and preprocessing (e.g., CIFAR-10, Caltech101, or custom datasets)  
- Data visualization (grayscale vs. color images)  
- Linear regression model implementation for baseline comparison  
- Custom CNN model design and training  
- Performance monitoring via loss plots and metrics  
- Side-by-side comparison of predicted color images and ground truth  

## Files

- `Image_Colorization.ipynb`: The main Jupyter notebook that contains the full analysis, model development, training, and evaluation steps.

## Technologies Used

- Python  
- NumPy  
- Matplotlib  
- Seaborn  
- PyTorch
- Scikit-learn  
- Jupyter Notebook  

## Highlights

- Demonstrates the limitations of linear regression for image colorization  
- Implements a custom shallow CNN for effective colorization  
- Includes visualizations of predictions compared to ground truth  
- Provides loss trend analysis across training epochs  
