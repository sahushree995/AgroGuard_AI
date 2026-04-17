# Plant Disease Detection Using Deep Learning

## Overview
This project focuses on detecting plant diseases using deep learning techniques. The system takes an image of a plant leaf as input and predicts whether the plant is healthy or affected by a specific disease. The goal is to assist farmers and agricultural professionals in early disease detection and improve crop productivity.

---

## Features
- Image-based plant disease detection
- Supports binary and multi-class classification
- Real-time prediction using a trained deep learning model
- User-friendly interface for uploading images
- Fast and efficient inference

---

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas
- OpenCV
- FastAPI (Backend)
- React (Frontend)

---

## Dataset
The model is trained using the PlantVillage dataset, which contains labeled images of plant leaves across multiple disease categories.

Dataset includes:
- Healthy leaves
- Multiple disease classes
- Different plant species

---

## Model Details
- Model Type: Convolutional Neural Network (CNN)
- Architecture: EfficientNet-B0 (pretrained) + custom layers
- Input Size: 224 × 224 images
- Output: Disease classification

### Preprocessing Steps:
- Image resizing
- Normalization
- Data augmentation (flip, rotation)

---

## System Architecture
The system follows a three-layer architecture:

1. Frontend: User uploads image
2. Backend: Handles API requests and processing
3. Model: Predicts disease from image

Flow:
User → Frontend → Backend → Model → Result

---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection
