# Multilayer Perceptron Tutorial: Depth vs Width Analysis

## Student Details
- Name: Vinay Kumar Pasupuleti  
- Student ID: 24109101  
- Module: Machine Learning and Neural Networks  

## Overview
This project investigates how neural network architecture affects performance by comparing depth (number of layers) and width (number of neurons per layer) in Multilayer Perceptrons using the Fashion-MNIST dataset.

## Project Structure
mlp-depth-vs-width-tutorial/
- MLP_Depth_vs_Width_Analysis_24109101.ipynb  
- MLP_Depth_vs_Width_Tutorial_24109101.pdf  
- README.md  
- LICENSE  

## Dataset
Fashion-MNIST (60,000 training, 10,000 test images, 10 classes, 28×28 grayscale).

## Methodology
- Depth: 1, 3, 5 layers (width = 128)  
- Width: 32, 128, 512 neurons (depth = 2)  
- Optimiser: Adam  
- Epochs: 20  
- Batch size: 128  

## Results
- Width improves performance more than depth  
- Best model: Width-512  
- Wider models achieve better accuracy and generalisation  

## Visualisations
- Depth accuracy  
- Width accuracy  
- Final accuracy  
- Generalisation gap  
- Training time  
- Confusion matrix  
- Training vs validation accuracy  

## How to Run
pip install tensorflow numpy pandas matplotlib scikit-learn  
Run the notebook file step by step.

## Ethics & Accessibility
- Dataset bias and computational cost considered  
- Clear graphs and structured layout used  

## Author
Vinay Kumar Pasupuleti (24109101)

## License
MIT License
