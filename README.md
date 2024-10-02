# MSFT Stock Price Prediction

## Overview
This project aims to predict Microsoft (MSFT) stock prices using various machine learning models, including LSTM, CNN, FCNN, and SVR. The goal is to evaluate the performance of these models and visualize their predictions to gain insights into stock price trends.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [License](#license)

## Installation
To run this project, ensure you have Python installed along with the following libraries:

```bash
pip install numpy pandas matplotlib scikit-learn torch
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/bkurtulmus/MSFT-Stock-Price-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MSFT-Stock-Price-Prediction
   ```
3. Run the Jupyter Notebook or Python scripts to train and evaluate the models.

## Models
This project implements the following models:
- **LSTM (Long Short-Term Memory)**
- **CNN (Convolutional Neural Network)**
- **FCNN (Fully Connected Neural Network)**
- **SVR (Support Vector Regression)**

Each model's performance is evaluated using Root Mean Squared Error (RMSE) on both training and testing datasets.

## Results
The project includes visualizations of model predictions compared to actual stock prices, allowing for an easy interpretation of performance. The results are saved in a CSV file for further analysis.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
