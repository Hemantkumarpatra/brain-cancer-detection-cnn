# 🧠 Brain Cancer Detection using Deep Learning (CNN)

This project aims to detect brain tumors (cancerous and non-cancerous) from MRI images using a Convolutional Neural Network (CNN). The model was trained on a labeled dataset of brain MRI scans to classify images into different categories such as **Tumor** and **No Tumor**.

---

## 🚀 Features

- Brain MRI image classification using Deep Learning
- High accuracy with CNN architecture
- Image preprocessing and augmentation
- Google Colab compatible
- Pretrained model included (hosted on Google Drive)


## 📁 Dataset

- The dataset contains labeled MRI images of brains categorized into:
  - **Tumor**
  - **No Tumor**

You can download a similar dataset from Kaggle:
🔗 [Brain Tumor Dataset on Kaggle](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)

---

## 📊 Model Architecture

- Convolutional Neural Network (CNN)
- Layers:
  - Conv2D
  - MaxPooling2D
  - Dropout
  - Flatten
  - Dense (with ReLU and Softmax)

---

## 🧠 Pretrained Model (Download Link)

⚠️ Due to GitHub file size restrictions, the trained model is **not uploaded here**.

👉 Download the model weights from Google Drive:

📥 [Download brain_cancer_model.h5](https://drive.google.com/file/d/1GZHQbe-v5oxywnKgkhax4sFczOJpMWaX/view?usp=drive_link)

---

## 🧪 How to Run

1. Open the notebook in **Google Colab**:
   [Notebook Link](https://colab.research.google.com/github/Hemantkumarpotra/brain-cancer-detection-cnn/blob/main/brain_cancer_detection.ipynb)

2. Mount your Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')

