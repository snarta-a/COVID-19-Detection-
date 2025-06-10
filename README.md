# 🧠 COVID-19 Detection in Chest X-rays using Deep Learning Algorithms

![COVID X-ray](https://img.shields.io/badge/DeepLearning-CNN-blue) ![Frameworks](https://img.shields.io/badge/Frameworks-TensorFlow%20%7C%20PyTorch-red) ![License](https://img.shields.io/badge/License-MIT-green)

A deep learning-based image classification project aimed at detecting COVID-19 from chest X-ray images using popular CNN architectures: **ResNet50**, **VGG16**, and **AlexNet**. This project is implemented using both **TensorFlow** and **PyTorch**, trained on a dataset of over **1600 chest X-ray images**.


---

## 📌 Project Overview

The goal of this project is to detect the presence of COVID-19 infection from chest X-ray images using deep learning models. Early detection through X-ray imaging can significantly help in fast and non-invasive diagnosis, especially in remote and resource-limited areas.

---

## 📂 Dataset

- **Source:** [COVID-19 Radiography Database - Kaggle](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database)
- **Total Images Used:** 1600+
  - COVID-19 Positive
  - Normal (Healthy)
- **Preprocessing:**
  - Image resizing
  - Normalization
  - Data augmentation (optional)

---

## 🧠 Models Used

The following Convolutional Neural Networks (CNNs) were used:
| Model     | Framework    | Transfer Learning |
|-----------|--------------|-------------------|
| ResNet50  | TensorFlow & PyTorch | ✅ Yes          |
| VGG16     | TensorFlow & PyTorch | ✅ Yes          |
| AlexNet   | PyTorch Only | ✅ Yes             |

---

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/COVID-19-Detection-in-Chest-Xrays-using-Deep-Learning-Algorithms.git
   cd COVID-19-Detection-in-Chest-Xrays-using-Deep-Learning-Algorithms
