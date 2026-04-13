# Deepfake Image Detection using MTCNN
## Authors
- K.Pragnasree  (Y22ACS470)
- P.Naga Tejasri  (Y22ACS537)
- G.Sravani  (Y22ACS452)
- M.Kranthi Kumar (Y22ACS503)

### Implementation
AI Agent Server, Bridge Server, and Notification Scheduler implementation.

🔗 https://github.com/Y22ACS470/Deepfake/tree/main

## Overview

Deepfake Image Detection Using MTCNN is an AI-powered system designed to identify whether an image is real or fake. With the increasing misuse of deepfake technology, this system provides a reliable solution to detect manipulated images.

The system first detects faces in an image using MTCNN, preprocesses the detected region, and then classifies it using a deep learning model. It helps in preventing misinformation and improving digital security.

---

## Project Components

### 1. Face Detection Module (MTCNN)
- Detects faces in input images
- Extracts facial regions
- Performs face alignment and normalization  

### 2. Preprocessing Module
- Crops detected faces
- Resizes images to fixed dimensions
- Normalizes pixel values

### 3. Classification Model
- Uses EfficientNet-B0  
- Performs binary classification (Real / Fake) 
- Outputs probability score

### 4. Web Interface
- Built using Flask  
- Allows users to upload images
- Displays prediction results (Real / Fake / No Face Detected)

---

## System Architecture
The system integrates multiple components including:

- Image Upload Interface
- Face Detection using MTCNN
- Preprocessing Pipeline
- Deep Learning Classification Model
- Result Visualization
These components work together to provide accurate deepfake detection.

---

## Technologies Used

### Backend
- Python  
- Flask  
- PyTorch  
- TensorFlow  

### Libraries
- OpenCV (cv2)  
- NumPy
- Matplotlib
- Face Recognition  

### Models
- MTCNN (Face Detection)
- EfficientNet-B0 (Classification) 

---

## Key Features
- Deepfake image detection using AI  
- Accurate face detection with MTCNN
- Image preprocessing and normalization
- Binary classification (Real / Fake) 
- Web-based user interface
- Fast and efficient predictions

---


---

## Research Contribution
This project demonstrates how Deep Learning and Computer Vision techniques can be used to detect manipulated media. It highlights the importance of preprocessing (face detection and alignment) in improving model accuracy for deepfake detection.

---



Department of Computer Science and Engineering  
Bapatla Engineering College

---

## Future Work
- Extend to video-based deepfake detection
- Real-time detection using webcam  
- Integration with social media platforms 
- Improve accuracy using advanced models (Transformers, GAN detection)
- Mobile application development

## GitHub Repositories

The source code for the EduPlus system is available in the following repositories:

### Backend Servers

🔗 https://github.com/Y22ACS470/Deepfake/tree/main
