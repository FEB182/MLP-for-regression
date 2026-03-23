# Neural Network (MLP) for California Housing Price Prediction

This project demonstrates how to build, train, and evaluate a **Multilayer Perceptron (MLP)** neural network to predict house prices using the **California Housing dataset**. 
The main goal is to provide a clear and practical understanding of how neural networks work, from data preprocessing to model evaluation.

## Dataset

The dataset used is the **California Housing Prices dataset**, which includes features such as:

- Longitude and latitude  
- Housing median age  
- Total rooms and households  
- Population  
- Median income  
- Median house value (target variable)  

## Project Workflow

The project follows a standard Machine Learning pipeline: Data Loading, Data Preprocessing, Train/Test Split, Model Training, Model Evaluation, Visualization

## Model Architecture

- Hidden layers: `(64, 32)`  
- Activation function: ReLU (default)  
- Optimizer: Adam (default)  
- Max iterations: 300  

## Results

The model performance is evaluated using:

- **MAPE** → Error in percentage  
- **R²** → Model explanatory power  
