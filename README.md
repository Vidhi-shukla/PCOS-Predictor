# PCOS Prediction Using Machine Learning

![OUTPUT](https://github.com/user-attachments/assets/e65a41fe-29cd-4a6b-9a83-52992b56f18f)


## Project Overview

**PCOS Prediction** is a machine learning-based tool designed to assist in diagnosing Polycystic Ovary Syndrome (PCOS) by analyzing ovarian ultrasound images. This project automates the classification process, which typically requires manual interpretation by specialists, making the process faster and less prone to human error.

The project uses machine learning models to classify ovarian images into two categories:
- **Infected (PCOS)**: Indicates the presence of PCOS in the ovarian image.
- **Not Infected (Healthy)**: Indicates that the ovaries are healthy with no signs of PCOS.

## Models Included

The project implements and compares the performance of both traditional machine learning and deep learning models, including:
- **Support Vector Machine (SVM)** (`SVM.py`)
- **Convolutional Neural Network (CNN)** (`CNN.py`)

Each model is evaluated based on metrics like accuracy, precision, recall, and F1-score. The performance results help determine which model performs best for detecting PCOS in ultrasound images.

## Motivation

Detecting PCOS can be challenging as the analysis of ovarian ultrasound images is often subject to variability between different clinicians. By leveraging machine learning, this project provides an objective, data-driven solution to diagnosing PCOS, with the following goals:
- Increase diagnostic accuracy
- Automate the analysis of ovarian ultrasound images
- Enable earlier detection and treatment of PCOS

## How It Works

1. **Data Collection**: Ultrasound images of ovaries are collected and categorized as either "Infected (PCOS)" or "Not Infected (Healthy)".
2. **Preprocessing**: The images are processed to ensure consistency in format and quality, making them suitable for model training.
3. **Modeling**: Machine learning models like SVM and CNN are trained to classify the ovarian images into the two categories based on their features.
4. **Prediction**: Once trained, the models can predict the classification of new ovarian images, determining whether they show signs of PCOS or not.

## Results

By comparing the SVM and CNN models, the project identifies which algorithm offers the highest accuracy and precision in detecting PCOS. These results are further analyzed using evaluation metrics to improve and fine-tune the model’s performance.

