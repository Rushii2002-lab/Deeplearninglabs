# Research Paper Implementation: YOLOv7 - Real-Time Object Detection and Segmentation

## 📘 Paper Title
**YOLOv7: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors**  
**Authors:** Chien-Yao Wang, Alexey Bochkovskiy, Hong-Yuan Mark Liao  
**Paper Link:** [arXiv:2207.02696](https://arxiv.org/abs/2207.02696)

---

## 🎯 Objective
The goal of this project is to reproduce and evaluate the YOLOv7 model for object detection and instance segmentation tasks using a real-world dataset. This includes:

- Reproducing the YOLOv7 model using the official repository
- Fine-tuning the pre-trained weights on a custom dataset
- Visualizing results and comparing performance with the original paper
- Evaluating the model using metrics like mAP, precision, recall, and F1-score

---

## 🧠 Key Features of YOLOv7

- Supports real-time object detection and segmentation
- Pre-trained on COCO dataset with 80 object classes
- Uses E-ELAN for efficient learning
- Achieves state-of-the-art accuracy and speed on GPU

---

## 📂 Dataset

- **Name:** COCO 2017 (subset used for training)
- **Link:** [https://cocodataset.org/#download](https://cocodataset.org/#download)
- **Description:** 80 object classes with bounding boxes, segmentation masks, and keypoints.

---

## 🛠️ Setup Instructions

### 1. Clone the YOLOv7 Repository

```bash
git clone https://github.com/WongKinYiu/yolov7
cd yolov7

