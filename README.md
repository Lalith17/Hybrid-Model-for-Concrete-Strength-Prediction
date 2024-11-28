# Hybrid Machine Learning Model for Compressive Strength Prediction

## Overview

This repository contains the code and research paper for our study on predicting the compressive strength of concrete using a hybrid machine learning model. The model integrates **CatBoost**, **Artificial Neural Networks (ANN)**, and a **linear regression meta-layer** to provide accurate predictions. Our hybrid approach outperforms individual models, offering an effective solution for construction engineers to predict concrete strength more efficiently.

## Research Paper

The full research paper is included in this repository. The paper presents the methodology, results, and future directions for the proposed hybrid model.

## Key Contributions

- **Hybrid Model**: A combination of CatBoost, ANN, and linear regression to predict concrete compressive strength.
- **Dataset**: A publicly available concrete dataset containing features like cement content, water ratio, aggregates, and more.
- **Evaluation**: The hybrid model achieved an **RMSE** of **3.86** and an **R²** score of **0.94**, outperforming individual models.
- **Real-world Application**: This approach provides a reliable tool for predicting concrete strength and optimizing construction material compositions.

## Usage

To train the model and evaluate its performance, follow these steps:

1. **Preprocess the data**: Run the data preprocessing script to clean and scale the data:

2. **Train the model**: Run the model script to train the hybrid model:

3. **Evaluate the model**: To get the evaluation metrics (RMSE, R²), run:

The output will show the performance metrics of the hybrid model as well as comparison with standalone models.

## Results

- **Hybrid Model**: RMSE = 3.86, R² = 0.94

## Future Work

- **Real-Time Prediction**: Integrating the model with IoT sensors for real-time predictions.
- **Dataset Expansion**: Incorporating a wider range of concrete mixtures to improve model generalization.
- **Model Optimization**: Further hyperparameter tuning and exploration of advanced machine learning techniques like transfer learning.
