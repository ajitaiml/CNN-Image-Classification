# CNN-Based Image Emotion Classifier 🚀🧠

This is a web application built using **Flask** and a **Convolutional Neural Network (CNN)** model trained with **TensorFlow/Keras**. The app allows users to **upload an image**, and the model predicts the **emotion** displayed — either **Happy** or **Sad** — based on facial features.

---

## 🗂️ Project Structure
CNN-Image-Classification/
│
├── app.py # Flask web application
├── imageclassifier.h5 # Trained CNN model (Keras format)
├── uploads/ # Folder to store uploaded images (auto-created)
├── logs/ # Log directory (ignored in git)
├── models/ # Optional: store training model versions
├── pycache/ # Python cache (ignored in git)
├── tf_env/ # Your Python virtual environment (ignored in git)
├── .gitignore # Git ignore configuration
├── requirements.txt # All dependencies listed for the project
└── README.md # This documentation



---

## 💻 Features

- Upload an image via a simple HTML form.
- Classifies the image into **"Happy"** or **"Sad"**.
- Displays prediction confidence.
- Built using **Flask** backend and **HTML frontend**.
- Deploy-ready for local use and platforms like **Render**, **Heroku**, etc.

---

## ⚙️ How It Works

1. **User uploads an image** through a browser.
2. The Flask app saves it temporarily in the `uploads/` folder.
3. The image is **preprocessed** (resized, normalized).
4. It is passed to the **CNN model** for prediction.
5. The result is shown directly on the web page.

---

## 🧠 Model Details

- Built using **TensorFlow** and **Keras**.
- Image input size: `256x256`
- Binary classification: `Happy (0)` and `Sad (1)`
- The model is stored in `imageclassifier.h5`.

---

## 📝 Sample Output

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ajitaiml/CNN-Image-Classification.git
   cd CNN-Image-Classification





