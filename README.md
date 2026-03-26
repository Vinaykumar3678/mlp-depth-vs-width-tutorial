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
- requirements.txt  
- LICENSE  

## Dataset
Fashion-MNIST (60,000 training images, 10,000 test images, 10 classes, 28×28 grayscale).

## Methodology
- Depth: 1, 3, 5 layers (width = 128)  
- Width: 32, 128, 512 neurons (depth = 2)  
- Optimiser: Adam  
- Epochs: 20  
- Batch size: 128  

## Results
- Width improves performance more than depth  
- Best model: Width-512  
- Wider models achieve higher accuracy and better generalisation  

## Visualisations
- Depth accuracy  
- Width accuracy  
- Final test accuracy  
- Generalisation gap  
- Training time  
- Confusion matrix  
- Training vs validation accuracy  

## Requirements
Install dependencies:
pip install tensorflow numpy pandas matplotlib scikit-learn

## How to Run
Open the notebook and run all cells:
MLP_Depth_vs_Width_Analysis_24109101.ipynb

## Ethical Considerations
- Dataset bias may limit real-world generalisation  
- Larger models require more computational resources  
- Misclassification may impact real-world applications  

## Accessibility
- Clear graphs with labelled axes and legends  
- Structured and readable format  
- Simple and consistent presentation  

## Author
Vinay Kumar Pasupuleti (24109101)

## License
This project is licensed under the MIT License.
