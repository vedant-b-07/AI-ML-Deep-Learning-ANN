# AI & Machine Learning - Task 6

## Deep Learning Fundamentals & Neural Network Implementation

This project implements a Neural Network for breast cancer classification
using Keras.

## Dataset

Breast Cancer Wisconsin (Diagnostic) Dataset.

## Neural Network Architecture

30 Input Features
↓
Dense Layer - 16 neurons - ReLU
↓
Dense Layer - 8 neurons - ReLU
↓
Output Layer - 1 neuron - Sigmoid

## Training

- Optimizer: Adam
- Loss Function: Binary Cross-Entropy
- Epochs: 50
- Batch Size: 16
- Validation Split: 20%
- Train/Test Split: 80/20

## Results

| Model | Test Accuracy |
|---|---:|
| Logistic Regression | 97.37% |
| Random Forest | 96.49% |
| Neural Network | 97.37% |

## Project Files

- `Task6_Deep_Learning_ANN.ipynb` - Complete implementation
- `Task6_Short_Report.docx` - Short report
- `accuracy_plot.png` - Training/validation accuracy
- `loss_plot.png` - Training/validation loss
- `model_comparison.csv` - Model comparison results