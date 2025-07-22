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

| Feature     | Description                        |
|-------------|------------------------------------|
| Images      | Input images for classification    |
| Labels      | Emotional states (happy, sad, etc.)|
| Models      | Trained CNN model (`imageclassifier.h5`) |

---

## 🛠 Tech Stack

<table> <tr> <th>Category</th> <th>Tool</th> <th>Usage</th> </tr> <tr> <td><strong>Programming Language</strong></td> <td><img src="https://cdn.worldvectorlogo.com/logos/python-5.svg" alt="Python" width="30"/> <strong>Python</strong></td> <td>Core language used for building the entire pipeline</td> </tr> <tr> <td><strong>Modeling</strong></td> <td><img src="https://cdn.worldvectorlogo.com/logos/tensorflow-2.svg" alt="TensorFlow" width="30"/> <strong>TensorFlow</strong></td> <td>Deep learning framework used to build and train the CNN model</td> </tr> <tr> <td><strong>Modeling</strong></td> <td><img src="https://upload.wikimedia.org/wikipedia/commons/a/ae/Keras_logo.svg" alt="Keras" width="30"/> <strong>Keras</strong></td> <td>High-level neural networks API running on top of TensorFlow</td> </tr> <tr> <td><strong>Preprocessing</strong></td> <td><img src="https://upload.wikimedia.org/wikipedia/commons/3/32/OpenCV_Logo_with_text_svg_version.svg" alt="OpenCV" width="30"/> <strong>OpenCV</strong></td> <td>Used for reading, resizing, and preprocessing image data</td> </tr> <tr> <td><strong>Notebook Environment</strong></td> <td><img src="https://cdn-icons-png.flaticon.com/512/5968/5968705.png" alt="Jupyter" width="30"/> <strong>Jupyter Notebook</strong></td> <td>Interactive environment for writing and executing Python code</td> </tr> <tr> <td><strong>Version Control</strong></td> <td><img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" alt="Git" width="30"/> <strong>Git & GitHub</strong></td> <td>Used for version control and project collaboration</td> </tr> </table>

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
