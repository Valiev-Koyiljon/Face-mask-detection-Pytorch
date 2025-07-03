# Face Mask Detection – PyTorch

[![Watch the Demo](https://img.youtube.com/vi/xf0f9s3kzEg/0.jpg)](https://youtu.be/xf0f9s3kzEg?si=YHPNR1BMKbEXFjK2)

**🎥 Click the image above to watch a live demo of this project on YouTube.**

---

## 🧠 Project Overview

This project detects whether a person is wearing a **face mask** in real time using deep learning and computer vision. Built with **PyTorch**, **OpenCV**, and **MTCNN**, it classifies faces as either:

* 😷 **With Mask**
* 😶 **Without Mask**

It promotes public health by enabling real-time monitoring using a webcam, and is trained on labeled image data.

---

## 📁 Dataset

The dataset used is provided in `mask_images_ready.zip`, containing labeled images split into:

* `with_mask`
* `without_mask`

To use the dataset:

1. Download `mask_images_ready.zip`
2. Extract it into your project directory
3. Use it for training/testing the model

---

## ⚙️ Installation

Ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
```

**Required Versions:**

* Python ≥ 3.6
* `torch==2.0.1`
* `torchvision==0.9.1`
* `MTCNN==0.1.12`
* `opencv-python==4.5.3.56`
* `numpy==1.21.5`
* `Pillow==8.3.2`
* `matplotlib==3.7.1`

---

## 🚀 How to Use

### 1. Train the Model

Open and run the following notebook in **Google Colab** or locally (with GPU support):

```
model.ipynb
```

* Follow in-notebook instructions
* Ensure your dataset is organized as `with_mask/` and `without_mask/`
* Train and save your model

### 2. Real-Time Inference

After training:

Open this notebook in **Jupyter Notebook** or **JupyterLab** (⚠️ Not Google Colab):

```
realTimeDetection.ipynb
```

* Connect a webcam
* Run the notebook to begin real-time face mask detection

---

## ⚠️ Notes

* **Colab users**: Google Colab cannot access your local webcam, so use it only for training.
* **Webcam access**: For real-time detection, ensure your device has a functional camera and use Jupyter locally.

---

## 💡 Technologies Used

* PyTorch
* OpenCV
* MTCNN (Face Detection)
* Python
* Jupyter Notebook
* Google Colab

---

## 📽 Demo

▶️ Watch the live demo here: [https://youtu.be/xf0f9s3kzEg](https://youtu.be/xf0f9s3kzEg?si=YHPNR1BMKbEXFjK2)


