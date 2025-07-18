# 🔥 CNN Image Classification

A deep learning project focused on classifying images using a Convolutional Neural Network (CNN). This project leverages TensorFlow for model building and training, and OpenCV for image preprocessing, supporting multiple emotion categories.

---

## 📌 Overview

This project implements a deep learning-based image classification system using a CNN, powered by TensorFlow and OpenCV. It categorizes images into different emotional states (e.g., happy, sad) by preprocessing images with OpenCV and training a robust model with TensorFlow, with options for CPU-only processing.

---

## 🧠 Machine Learning Workflow

- Data collection & preprocessing
- Model training using a CNN
- Model evaluation and saving
- Testing with sample images

---

## 📈 Features Used

| Feature     | Description                       |
|-------------|-----------------------------------|
| Images      | Input images for classification   |
| Labels      | Emotional states (happy, sad, etc.)|
| Models      | Trained CNN model (`imageclassifier.h5`) |

---

## 🛠 Tech Stack

| Layer       | Tools & Libraries                  |
|-------------|------------------------------------|
| Data        | PyCache, custom datasets           |
| ML Model    | TensorFlow/Keras (CNN)             |
| Image Processing | OpenCV                       |
| Processing  | CPU-only (Getting_Started_CPU_Only.ipynb) |
| Versioning  | Git & GitHub                       |

---

## 🗂 Project Structure – CNN Image Classification

| Path                        | Description                                                  |
|-----------------------------|--------------------------------------------------------------|
| `CNN-ImageClassification/` | Main project directory                                      |
| ├── `pycache_`             | Cached Python files                                         |
| ├── `data/`                | Directory for image datasets                                |
| │   ├── `happy/`           | Images labeled as happy                                     |
| │   ├── `sad/`             | Images labeled as sad                                       |
| │   ├── `logs/`            | Training logs                                               |
| │   └── `models/`          | Saved model files                                           |
| │       └── `imageclassifier.h5` | Trained CNN model file                        |
| ├── `Test Data/`           | Directory for test images                                   |
| │   ├── `download(1).jpg`  | Sample test image                                           |
| │   ├── `image.jpg`        | Sample test image                                           |
| │   └── `image.png`        | Sample test image                                           |
| ├── `.gitignore`           | Git ignore file                                             |
| ├── `Getting_Started_CPU_Only.ipynb` | Notebook for CPU-only setup and training    |
| ├── `imageclassifier.h5`   | Alternative saved model file                                |
| ├── `requirements.txt`     | Python dependencies for the project                         |
| └── `tf.env`               | TensorFlow environment configuration                        |
