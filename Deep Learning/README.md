# Deep Learning Project

## Team Members
- Alice
- Davide
- Alberto

## Overview
This project, collaboratively carried out by Alice, Davide, and Alberto, aims to predict the outcome of the 'RainTomorrow' variable, which indicates whether it will rain tomorrow ('Yes') or not ('No').

### Preprocessing
- **File:** `PreProcessing.ipynb`
- **Details:** This notebook contains the data cleaning process, focusing on handling missing values, which posed a significant challenge.

### Approach
We adopted three different methods to handle missing values. For each method, we trained and optimized a neural network. The outcomes of these models were then compared to select the best approach for this prediction task.

### Model Optimization
- **Oversampling:** `Modeling_Oversampling.ipynb`
  - This notebook demonstrates the impact of oversampling the majority class on neural network training.
- **Undersampling:** `Modeling_Undersampling.ipynb`
  - This notebook details the optimization of models after applying undersampling techniques to balance the two classes (Yes/No).

### Dataset
- The dataset utilized for this project is available [here](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package).

This project represents our combined effort to address a common challenge in deep learning: effectively predicting outcomes based on weather data, while tackling the issue of imbalanced datasets.

