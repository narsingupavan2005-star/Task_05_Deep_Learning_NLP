# Task 5 - Deep Learning NLP SMS Spam Classifier

## Project Overview

This project implements a Deep Learning based SMS Spam Classification system using PyTorch.

The system classifies SMS messages into two categories:

- Ham
- Spam

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- Matplotlib

## Dataset

The project uses the SMS Spam Collection dataset.

The dataset contains SMS messages labeled as either ham or spam.

## NLP Preprocessing

The following preprocessing steps were performed:

1. Dataset loading
2. Missing value checking
3. Duplicate removal
4. Label encoding
5. Train-test splitting
6. TF-IDF vectorization

## Deep Learning Model

A multi-layer neural network was implemented using PyTorch.

The architecture includes:

- Linear layers
- ReLU activation
- Batch Normalization
- Dropout
- Adam optimizer
- Binary Cross-Entropy loss

## Training

The model was trained using training and validation datasets.

Early stopping was implemented to reduce overfitting.

Training and validation loss and accuracy curves were plotted.

## Evaluation

The model was evaluated using:

- Test Accuracy
- Classification Report
- Confusion Matrix

## Sample Inference

The trained model was tested on unseen SMS messages and produced:

- Predicted class
- Spam confidence score

## Project Files

- `task_05_nlp_classifier.ipynb` - Complete Jupyter Notebook
- `best_spam_classifier.pth` - Saved PyTorch model
- `SMSSpamCollection` - Dataset

## Conclusion

This project demonstrates a complete NLP deep learning pipeline for SMS spam detection, from TF-IDF feature extraction and neural network training to evaluation and prediction on unseen messages.