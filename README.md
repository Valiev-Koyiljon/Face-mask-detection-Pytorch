# Face-mask-detection-Pytorch

This project aims to detect whether a person is wearing a face mask in real time using computer vision techniques. It uses a pre-trained deep learning model to classify images into two categories: "with mask" and "without mask."

Face Mask Detection: PyTorch, OpenCV, Python, and MTCNN is used for this project. It combines deep learning, computer vision, and real-time video processing. Trained on labeled data, the system evaluates accuracy and loss. Promote public health and safety with this mask detection solution.
 
 

## Dataset

The dataset used for this project is available in the "mask_images_ready.zip" file. It contains a collection of labeled images, with each image labeled as "with mask" or "without mask." The dataset is divided into training and testing sets for model training and evaluation.

To use this dataset, download the "mask_images_ready.zip" file and extract it to the appropriate location in your project directory.

## Installation

To run this project locally, please ensure you have the following dependencies installed:

- Python 3.6 or above
- torch==2.0.1
- torchvision==0.9.1
- MTCNN==0.1.12
- numpy==1.21.5
- opencv-python==4.5.3.56
- Pillow==8.3.2
- matplotlib==3.7.1

You can install the required packages by running the following command:
**pip install -r requirements.txt**



## Usage

1. After installing the dependencies, navigate to the project directory.

2. Run the "Facemask_detection_last1_Final.ipynb" notebook. This notebook is used for training the deep learning model for face mask detection. Follow the instructions within the notebook to train the model using your own dataset of face images labeled as "with mask" or "without mask". Make sure to properly organize and label your dataset before training. You can use Google Colab for this part of the project to take advantage of its computing resources.

3. Once the model is trained and saved, open the "RealTimeFaceMaskDetecter.ipynb" notebook using Jupyter Notebook or JupyterLab (not Google Colab). This notebook is used for accessing the real webcam and performing real-time face mask detection using the trained model. Run the cells within the notebook to start the real-time face mask detection.

**Note:** Make sure to have a webcam connected to your system to capture the live video feed.

Please note that when running the second code file to access the web camera, please use Jupyter Notebook or JupyterLab instead of Google Colab. Google Colab may not work with this code because it has its own code to access the camera. However, you can still use Google Colab for the first part of our project to train the model.

## Facemask detection presentation
1. Due to the 25 MB limit on uploading the file to Github, I could not upload my ppt file directly. Therefore, If you are interested in my presentation about facemask detection, I will leave the link to download the file via Google Drive: https://drive.google.com/file/d/1vdoWcSmqZ4Ttn1GGLfBN0wKh9YRjKLKl/view

## Research Report
1. I wrote small resaearch report. I uploaded the file to the Github. If you are interseted in my report, you can download it directly from this repository. 



