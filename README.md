# Deepfake Video Detection Using InceptionResNetV2

## Overview
Deepfakes, AI-manipulated videos, are becoming a major threat. They can be used to spread misinformation and damage reputations. This project aims to combat deepfakes using InceptionResNetV2, a powerful AI model capable of identifying subtle inconsistencies that give away a deepfake, such as unnatural facial features or vocal anomalies.

## Motivation
The urgent need to safeguard our digital landscape from deepfake threats motivated this project. By developing a reliable detection system, we aim to empower individuals and institutions to critically evaluate online information, flag potential deepfakes, and verify video authenticity before publication.


## Introduction
### Overview
Deepfake technology poses a significant threat by spreading misinformation and damaging reputations. This project employs the InceptionResNetV2 model to detect deepfake videos effectively.

### Motivation
The project addresses the growing need to protect digital content from deepfake manipulation, aiming to build a reliable detection system for social media platforms, news outlets, and individuals.

## InceptionResNetV2: A Convolutional Neural Network for Image Classification

InceptionResNetV2 is a convolutional neural network (CNN) architecture developed by Google for image classification. It combines elements from two successful architectures: Inception and ResNet.

- **Inception modules**: These modules process information at different scales simultaneously, capturing more diverse features from the input image.
- **Residual connections**: These connections skip over some layers in the network, alleviating the vanishing gradient problem and allowing for deeper networks with better performance.

InceptionResNetV2 has achieved state-of-the-art results on various image classification benchmarks, demonstrating its effectiveness in extracting meaningful features from images.

## Deepfake Video Detection with InceptionResNetV2

Deepfakes are realistic manipulated videos created using machine learning techniques. Detecting deepfakes is crucial for mitigating their harmful effects, such as the spread of misinformation and identity theft.

InceptionResNetV2 can be used for deepfake video detection in several ways:

- **Feature extraction**: The network can extract features from video frames, focusing on facial features, skin texture, and other visual cues that might reveal inconsistencies in manipulated videos.
- **Temporal analysis**: By analyzing features from multiple frames sequentially, InceptionResNetV2 can identify unnatural motion patterns or inconsistencies in blinking, often present in deepfakes.
- **Transfer learning**: A pre-trained InceptionResNetV2 model can be fine-tuned on a dataset of real and fake videos, leveraging its learned features for more efficient deepfake detection.

## Advantages of InceptionResNetV2 for Deepfake Detection

- **Strong image classification performance**: InceptionResNetV2 excels at extracting relevant features from images, which is essential for deepfake detection.
- **Efficient architecture**: The combination of Inception modules and residual connections makes InceptionResNetV2 relatively efficient, allowing for real-time video processing in some applications.
- **Pre-trained models available**: Pre-trained models on large image datasets are readily available, reducing training time and effort for deepfake detection tasks.

## Project Files - https://drive.google.com/drive/folders/1LtE0_iRclqr8xwA3ZZAEaQEZFwhAsYMR?usp=drive_link


![Screenshot 2024-04-15 105749](https://github.com/SaiAkhileshP/Deepfake-Video-Detection-using-InceptionResNetV2/assets/101054891/3de02248-90b4-44e9-85f7-8fdf2d43b69b)
![result 5](https://github.com/SaiAkhileshP/Deepfake-Video-Detection-using-InceptionResNetV2/assets/101054891/853571d2-861b-43f3-84aa-89f9f40102e8)
![result 4](https://github.com/SaiAkhileshP/Deepfake-Video-Detection-using-InceptionResNetV2/assets/101054891/1643fe06-11c7-4233-9b56-b7fd27cd92cb)
![result 1](https://github.com/SaiAkhileshP/Deepfake-Video-Detection-using-InceptionResNetV2/assets/101054891/081b273c-53ee-4f18-877d-8d88b32a5fd3)
![Screenshot 2024-04-15 105840](https://github.com/SaiAkhileshP/Deepfake-Video-Detection-using-InceptionResNetV2/assets/101054891/da7c386c-21c6-406d-8dc4-413e0ba4422a)


