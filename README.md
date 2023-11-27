
# Healthy vs Unhealthy Plant Classification

This repository contains the code and models for a convolutional neural network designed to classify plant images as healthy or unhealthy.

## Contents

The repository contains code, data, models and results for the plant classification project.

## Summary

The project involved benchmarking various CNN architectures for transfer learning on the plant dataset. Data augmentation and regularization techniques were used to improve model generalization. The final model uses a ConvNeXt feature extractor with custom classification layers, and achieves 86.7% accuracy on the test set.

Key aspects and techniques explored include:

- Data cleaning and preprocessing
- Data augmentation (shifts, flips etc) 
- Transfer learning with VGG16, EfficientNet, ConvNeXt etc.
- CNN architecture search and tuning
- L1/L2 regularization, dropout
- Self-supervised pretraining (SimCLR)
- Test time augmentation

## Usage

Jupyter notebooks provide end-to-end examples of the model development pipeline. Pretrained models are provided for evaluation on new data.


## Authors

Luigi Pagani, Flavia Petruso, Federico Schermi

