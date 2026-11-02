<div align="center">

# 🐶 Dog Detection · YOLOv7 (local training)

**Train and run YOLOv7 dog detection on a local machine instead of the cloud.**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/YOLO-111F68?style=for-the-badge" alt="YOLO"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">

</div>

<p align="center"><img src="https://github.com/KamranUmer/yolov7-1/assets/86089489/d44972d5-4e5c-4849-96c4-ca1c134cdbba" alt="Dog Detection · YOLOv7 (local training) screenshot" width="85%"></p>

## 📌 Overview

A copy of the official YOLOv7 code base, set up to train a **dog detector** on a custom dataset on a local GPU rather than in Colab. The dataset covers many breeds, angles, backgrounds and lighting conditions.

## ✨ Features

- Full YOLOv7 training and inference scripts (`train.py`, `detect.py`, `test.py`, `export.py`)
- Custom dog dataset with bounding-box annotations
- Demo results on images and video
- Training runs archived in `runs.zip`

## 🚀 Getting Started

```bash
git clone https://github.com/KamranUmer/yolov7-1.git
cd yolov7-1
pip install -r requirements.txt
python train.py --data data/custom.yaml --cfg cfg/training/yolov7.yaml --weights yolov7.pt --epochs 100
python detect.py --weights runs/train/exp/weights/best.pt --source your_image.jpg
```

Adjust the dataset YAML and paths to your own data.

## 🙏 Acknowledgements

- [YOLOv7](https://github.com/WongKinYiu/yolov7) by WongKinYiu et al.. Most of the code in this repo is theirs (GPL-3.0); my part is the custom dataset, training and demo.

---

<div align="center">

Built by <a href="https://github.com/KamranUmer"><b>Kamran Umer</b></a> · ⭐ Star the repo if you find it useful

</div>
