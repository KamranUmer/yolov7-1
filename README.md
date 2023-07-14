# Dog Detection with YOLOv7 on local Machine(Computer)




# Demo :

This project contains a demo Image and Video of my project :point_down:

# Dog Detection:
This repository contains the code and resources for training a dog detection model using YOLOv7 on a custom dataset. YOLOv7 is a state-of-the-art object detection algorithm known for its accuracy and real-time performance. By leveraging YOLOv7, we can efficiently detect and locate dogs in images and videos.


# Dataset:
To train the dog detection model, we collected and annotated a custom dataset consisting of various dog breeds. The dataset includes images captured from different angles, backgrounds, and lighting conditions to ensure robustness. The annotations contain bounding box coordinates for each dog instance in the images.


# Model Training:
The training pipeline involves several steps, including data preparation, model configuration, training, and evaluation. Here's an overview of the training process:


# Data Preparation:
We divided the dataset into training and validation sets. Each image was resized and preprocessed to match the input requirements of the YOLOv7 model.

# Model Configuration:
YOLOv7 requires a configuration file specifying the model architecture and hyperparameters. We fine-tuned the configuration file according to our specific requirements, such as the number of classes (dog in our case) and anchor sizes.

# Model Training:
We trained the YOLOv7 model using the prepared dataset and configuration. The training involved optimizing the model's weights to minimize the detection loss and improve its ability to identify and locate dogs accurately.

# Model Evaluation:
To assess the performance of the trained model, we evaluated its accuracy on the validation set. We computed metrics such as precision, recall, and mean Average Precision (mAP) to measure the model's effectiveness in dog detection.

# Inference:
Once the model is trained and evaluated, it can be used for dog detection on new images or videos. We provide a script (inference.py) that takes an input image or video file and applies the trained model to detect dogs. The script outputs the detections, including the bounding box coordinates and confidence scores.


# Contact:
If you have any questions, suggestions, or would like to collaborate, feel free to reach out to us at kamranumer080@gmail.com. We appreciate your feedback!


# images:

![3](https://github.com/KamranUmer/yolov7-1/assets/86089489/d44972d5-4e5c-4849-96c4-ca1c134cdbba)


# Video:

[short of dog.zip](https://github.com/KamranUmer/yolov7-1/files/12046000/short.of.dog.zip)


