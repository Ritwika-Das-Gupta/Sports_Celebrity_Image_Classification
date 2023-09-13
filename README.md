
# Sports Person Image Classification

GitHub repository for a machine learning-based sports personality image classification system. This project covers data collection, preprocessing, model training, and performance evaluation. Open-source under the MIT License.

LINK TO DOWNLOAD THE IMAGES DATASET: https://drive.google.com/drive/folders/1vavIn1flpJv3LWHO6noYuUwuD2ETkoPU?usp=drive_link

## Introduction

Welcome to the Sports Person Image Classification project repository! This project focuses on utilizing machine learning techniques to recognize and classify images of sports personalities. Whether you're a sports enthusiast, developer, or researcher, this repository offers tools and resources for accurate image recognition in the world of sports.

## Table of Contents
- [Introduction](#introduction)
- [Key Features](#key-features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Testing with GUI](#testing-with-gui)


## Introduction

Recognizing sports icons in images is a valuable task in today's digital world. This project provides a solution for automated image classification of sports personalities, making it useful for sports apps, fan websites, and sports analytics tools.

## Key Features

- **Machine Learning Models**: Utilize state-of-the-art image classification techniques.
- **Data Collection**: Scripts for gathering sports personality images.
- **Data Preprocessing**: Tools to clean and preprocess the dataset.
- **Model Training**: Train models to recognize athletes and sports icons.
- **Evaluation Metrics**: Assess model accuracy and performance.

## Getting Started

### Overview

The code aims to detect and recognize faces of celebrities in images. It follows these key steps:

#### Importing Libraries and Loading an Image
#### Face Detection using Haar Cascade
#### Creating a Cropped Image
#### Feature Engineering with Wavelet Transform
#### Model Training (Support Vector Machine, SVM)
#### Model Selection using GridSearchCV
#### Saving the Trained Model and Class Dictionary
#### Creating a GUI for Image Upload and Testing

#### Face Detection using Haar Cascade

The code uses Haar Cascade classifiers to detect faces and eyes in the image. It makes use of OpenCV for this purpose.

#### Feature Engineering with Wavelet Transform

A wavelet transform is applied to the cropped image to enhance its features, making it easier to distinguish facial features like eyes, nose, and lips.

#### Model Training

The dataset is prepared for training the machine learning model. Both raw and wavelet-transformed images are used as features. The chosen model is a Support Vector Machine (SVM).

#### Model Selection using GridSearchCV

Different machine learning models and hyperparameters are explored using GridSearchCV to find the best-performing model.

#### Saving the Model

The trained model and a class dictionary that maps class labels to celebrity names are saved for later use.

#### Creating a GUI for Image Upload and Testing

Tkinter is used to create a graphical user interface (GUI) that allows users to upload an image for celebrity recognition.

#### Image Preprocessing and Prediction

When a user uploads an image, it undergoes preprocessing, face detection, feature engineering, and is then used for prediction. The recognized celebrity's name is displayed as the output.



This project is open-source and available under the MIT License.
