# SIGNATURE_VERIFICATION_USING-SIAMESE_NEURAL_NETWORK_ONE-SHOT_LEARNING


This repository contains code for a signature verification model developed using deep learning techniques. The model is trained to classify whether pairs of signatures belong to the same person or not.

## Table of Contents

- [Training Loop Outputs](#training-loop-outputs)
- [Plotting Metrics](#plotting-metrics)
- [Encoder Extraction](#encoder-extraction)
- [Classify Images](#classify-images)
- [Model Metrics](#model-metrics)
- [Usage](#usage)
- [Requirements](#requirements)
- [License](#license)

## Training Loop Outputs

During the training phase, the model outputs the loss and accuracy metrics for each epoch. The loss on the training data consistently remains 0, while the accuracy on the test data reaches around 98.33%.

## Plotting Metrics

The `plot_metrics` function is defined to visualize various metrics over epochs, including training loss, testing accuracy, means comparison, and quartile comparison.

## Encoder Extraction

The `extract_encoder` function is used to extract the encoder from the trained model. The encoder is then saved for later use.

## Classify Images

The `classify_images` function computes the distance between the encodings of two signature images and classifies them as "similar" or "different" based on a given threshold.

## Model Metrics

The `ModelMetrics` function computes and prints model accuracy and plots the confusion matrix based on the true and predicted classifications.

## Usage

To use the signature verification model, follow these steps:

1. Train the model using the provided training data.
2. Extract the encoder from the trained model.
3. Use the encoder to classify pairs of signature images as "similar" or "different" based on the distance between their encodings.

## Requirements

- Python
- TensorFlow
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn


