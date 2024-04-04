# Face Recognition

## Overview

This project focuses on implementing a face recognition system using traditional computer vision techniques without neural networks. The objective is to design a system that receives an image from the computer's webcam, recognizes the user's face, and allows access if the face matches a pre-defined set of images.

## Implementation

### Problem Statement

The project involves developing a face recognition system that prints "face is recognized" if the user's face exists in the incoming webcam image and "face is not recognized" if the face of anyone else but the user exists in the image. The system should use traditional computer vision networks to achieve this task.

### Data Collection

Data collection involves gathering a dataset consisting only of the user's face images. These images will be used to train the face recognition model.

### Model Training

Using traditional computer vision techniques, a model is trained to compare the input image from the webcam with the user's images. The model calculates the similarity between the faces and allows access if the similarity is higher than a certain threshold. In this project the model is One-Class SVM.

### Implementation Details

- The haarcascade_frontalface_default. xml is a haar cascade designed by OpenCV to detect the frontal face, that is used in this project.
- The system receives the webcam image and recognizes the user's face in a certain number of these images to allow access.

## Requirements

- OpenCV library
- Webcam or virtual webcam software
- Dataset containing user's face images

## Project Output
![Video-report](https://github.com/pooriaazizi-ce/Face-Recognition-AI/assets/99240766/23ba7424-81bb-4fa2-8b7d-38b41b174224)
