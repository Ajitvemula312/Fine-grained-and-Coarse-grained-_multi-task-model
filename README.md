# Multi-Task Learning with Enhanced ResNet50 Architecture

This README file provides an overview of the code in the "Multi Task Learning.ipynb" Jupyter Notebook, which demonstrates multi-task learning using an enhanced ResNet50 architecture. Multi-task learning involves training a single neural network to perform both fine-grained and coarse-grained image classification tasks simultaneously.

## Overview

The Jupyter Notebook contains code for multi-task learning using an enhanced ResNet50 architecture. It showcases multiple steps to improve model performance, making it suitable for real-world multi-task learning scenarios.

## Loading the Data

The code uses the CIFAR-100 dataset for multi-task learning. Images are loaded and preprocessed for both fine-grained and coarse-grained classification tasks.

## Initial Model

An initial custom neural network model is presented, but the accuracy results are relatively low.

## Fine-Tuning with Pre-trained ResNet50

To enhance performance, a pre-trained ResNet50 model is employed and fine-tuned for multi-task learning. This approach leads to a significant improvement in accuracy:

- Test Fine-grained Accuracy: 36.35%
- Test Coarse-grained Accuracy: 49.72%

## Further Enhancements for Improved Accuracy

The code showcases further adjustments made to the ResNet50-based model. These enhancements include introducing more dense layers, fine-tuning the learning rate, and modifying loss weights. These adjustments result in even better results:

- Test Fine-grained Accuracy: 43.43%
- Test Coarse-grained Accuracy: 60.93%

## Model Performance

Here are the performance results for the different models:

| Model Description                             | Fine-grained Accuracy | Coarse-grained Accuracy |
|----------------------------------------------|-----------------------|-------------------------|
| Initial Model                                 | 26.79%                | 38.64%                  |
| ResNet50 Model (before adjustments)          | 36.35%                | 49.72%                  |
| Enhanced ResNet50 Model (after adjustments)  | 43.43%                | 60.93%                  |

![Accuracy and Loss Plots](download (1).png)

The table summarizes the performance of the models, and the accompanying image shows accuracy and loss plots for the enhanced ResNet50 model. These results demonstrate the effectiveness of multi-task learning with the enhanced architecture. Further adjustments and fine-tuning can be explored to achieve even better performance.
