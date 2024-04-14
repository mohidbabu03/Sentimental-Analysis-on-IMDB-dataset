# Sentiment Analysis on IMDB Dataset

This repository contains code for comparing traditional machine learning models with recurrent neural network (RNN) models for sentiment analysis. The dataset used is a supervised one, comprising reviews labeled as positive or negative.

## Traditional Models:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

## RNN Models:
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)

Two variants of the dataset were utilized:
1. Full Dataset
2. Keras IMDb Dataset (considering only 10,000 reviews)

### Results:

### Traditional Models (Full Dataset):
- SVM: 90.03% accuracy
- Logistic Regression: 89.8% accuracy
- Random Forest: 85.55% accuracy
- KNN: 77.25% accuracy
- Decision Tree: 72.15% accuracy

### Keras IMDb Dataset (10,000 reviews):
- Random Forest: 53.32% accuracy
- SVM: 51.54% accuracy
- Logistic Regression: 51.78% accuracy
- Decision Tree: 51.31% accuracy
- KNN: 50.22% accuracy

### Recurrent Neural Network Models:
#### Training Accuracy:
- GRU: 96.15%
- LSTM: 95.95%

#### Validation Accuracy:
- GRU: 83.48%
- LSTM: 81.47%

In RNN models, GRU performed the best.
