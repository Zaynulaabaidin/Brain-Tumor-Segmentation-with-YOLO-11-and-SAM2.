# Brain-Tumor-Segmentation-with-YOLO-11-and-SAM2.
This project combines YOLO for brain tumor detection and SAM for precise segmentation of MRI images. It automates tumor localization and segmentation, providing valuable insights for healthcare professionals in diagnosing brain tumors. The pipeline enhances medical image analysis, enabling faster and more accurate tumor detection and segmentation.

# Project Overview
This project aims to detect and segment brain tumors from MRI images using a combination of object detection (YOLO) and segmentation (SAM2) techniques. The model identifies tumor regions accurately, which can assist medical professionals in diagnosis and treatment planning.

# Table of Contents
- Technologies Used
- Installation Instructions
- Dataset

# Technologies Used
- Python 3.13
- YOLOv11 — for object detection
- Segment Anything Model 2 (SAM2) — for image segmentation
- PyTorch — for deep learning model training
- Ultralytics — for YOLOv11 integration
- Google Colab

# Installation Instructions
To get started with this project, first clone the repository to your local machine. Next, install the required libraries by running the command pip install -r requirements.txt in your terminal or command prompt. Once the libraries are installed, open the project in your preferred code editor, such as VS Code, Jupyter Notebook, or Google Colab. Then, simply follow the instructions provided in the notebook to preprocess the dataset, train the model, and evaluate and visualize the results.

# Dataset
The dataset for this project is available on Roboflow. You can download it by visiting the Brain Tumor Dataset page [https://universe.roboflow.com/iotseecs/brain-tumor-yzzav/dataset/1]. After signing in or creating a Roboflow account, simply click the "Download Dataset" button to get the dataset in your preferred format (like YOLO or COCO). Once downloaded, extract the files to your local machine and use them in your project to train and test the model.
