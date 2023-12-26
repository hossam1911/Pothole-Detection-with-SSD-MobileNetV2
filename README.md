# Pothole Detection with SSD MobileNetV2

## Overview

This project focuses on detecting potholes in road images using computer vision techniques. The object detection model employed for this task is SSD MobileNetV2, a pretrained deep learning model that excels in real-time object detection.

## Dataset

The dataset consists of 665 images of roads with labeled potholes. The dataset is available on [Roboflow](https://public.roboflow.com/object-detection/pothole), making it accessible for training and evaluation.

## Model Architecture

The chosen model for this project is SSD MobileNetV2, a state-of-the-art deep neural network that balances speed and accuracy. The model is pretrained on a large dataset and fine-tuned on the pothole detection dataset.



```
-CustomTF2_2/
│
├── data/
│   ├── train/
│   │   ├── image1.xml
│   │   ├── image2.xml
│   │   └── ...
│   ├── test/
│   │   ├── image3.xml
│   │   ├── image4.xml
│   │   └── ...
│   ├── inference_graph/
│   │   ├── checkpoint
│   │   ├── eval
│   │   ├── Saved_model 
│   │   └── pipline config

│   ├── label_map.pbtxt
│   ├── ssd_mobilenet_v2_fpnlite_320x320_coco17_tpu-8.config
│   ├── train_labels.csv
│   ├── test_labels.csv
├── training/
│   ├── eval
│   ├── train
│   │   ├── events
│   ├── checkpoint

├── README.md
 └── ...

