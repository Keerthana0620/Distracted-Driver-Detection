# Distracted-Driver-Detection

## Project Overview

This project focuses on classifying distracted driver behaviors using images captured from inside vehicles. It aims to identify 10 classes of driver actions, such as texting, eating, or safely driving. By leveraging computer vision techniques, the goal is to build a model that can accurately detect and classify various forms of distracted driving to potentially improve road safety.

## Dataset

The dataset used for this project comes from the State Farm Distracted Driver Detection competition on Kaggle (https://www.kaggle.com/competitions/state-farm-distracted-driver-detection)
It consists of images in the following categories:

- Safe driving
- Texting - right
- Talking on the phone - right
- Texting - left
- Talking on the phone - left
- Operating the radio
- Drinking
- Reaching behind
- Hair and makeup
- Talking to a passenger

## Model

This project explores various deep learning architectures to classify distracted driver images. We trained models from scratch and also utilized popular pre-trained models for transfer learning. The models used include:

- Convolutional Neural Network (CNN): A custom-built model trained from scratch.
- ResNet50: A deep residual network designed to handle vanishing gradient problems with skip connections.
- MobileNet: A lightweight CNN model optimized for mobile and embedded vision applications.
- Xception: An extreme version of the Inception model with depthwise separable convolutions.
- VGG16: A deep convolutional network known for its simplicity and strong feature extraction capabilities.

## Results

The model is evaluated using accuracy and a confusion matrix to assess how well it classifies each of the 10 driver behaviors. The goal is to minimize misclassification, especially in categories like texting or talking on the phone, which pose significant road risks.
