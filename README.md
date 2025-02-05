# Jellyfish Image Classification using Deep Learning

## Project Overview

This project focuses on classifying jellyfish images into different species using **Deep Learning techniques**. The objective is to develop a model capable of identifying jellyfish species based on their physical characteristics.

## Dataset Description

The dataset consists of **900 images** of jellyfish belonging to six different categories:
1. **Mauve stinger jellyfish**
2. **Moon jellyfish**
3. **Barrel jellyfish**
4. **Blue jellyfish**
5. **Compass jellyfish**
6. **Lion’s mane jellyfish**

Deep Learning models are applied to extract features, classify species, and analyze jellyfish color variations.

## Problem Statement

Classifying jellyfish images is challenging due to:
- **Limited training data**: The difficulty of photographing jellyfish underwater leads to a small dataset.
- **Unclear images**: Jellyfish have colors similar to coral reefs, making it hard to differentiate them.

To overcome these challenges, **data augmentation** and **model optimization** techniques are implemented.

## Models Used

The following models were tested and evaluated:
1. **CNN Model**
2. **AlexNet**
3. **ConvNet**
4. **VGGNet**

## Model Performance

| Model  | Accuracy |
|--------|---------|
| CNN (Before Modification) | 68% |
| AlexNet | 55% |
| ConvNet | 62% |
| VGGNet | 56% |
| **CNN (After Modification)** | **92%** |

### Key Findings:
- **CNN performed best**, achieving **92% accuracy** after optimization.
- **Increasing the number of epochs** improved the model but also increased training time.
- **Performance optimization techniques** were applied, such as reducing the learning rate and using early stopping.

## Techniques Used

- **Data Augmentation**: Random shifts, zooming, and flipping to increase training data.
- **Hyperparameter Tuning**: Modifying epochs and learning rates to improve performance.
- **Performance Optimization**: Early stopping and optimizer selection to reduce overfitting.
