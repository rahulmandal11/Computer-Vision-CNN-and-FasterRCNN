# Computer Vision: CNN Analysis & Faster R-CNN Implementation

This repository contains two practical implementations covering fundamental and advanced concepts in Computer Vision using Deep Learning.

---

## 📌 Overview

This project is divided into two tasks:

### 🔹 Task 1: CNN Padding & Stride Analysis

* Study of how padding (`same` vs `valid`) affects feature extraction
* Impact of stride on spatial resolution and computation
* Evaluation using:

  * Accuracy
  * Training time
  * Number of parameters
* Visualization of feature maps and performance metrics

### 🔹 Task 2: Simplified Faster R-CNN Pipeline

* Implementation of object detection pipeline:

  * Backbone CNN
  * Anchor generation
  * Region Proposal Network (RPN)
  * ROI Pooling
  * Detection head (classification + bounding box regression)
* Visualization of anchors and detection outputs
* Demonstrates end-to-end detection workflow

---

## 🧠 Key Learnings

* Trade-offs between accuracy and efficiency in CNN design
* Importance of padding in preserving spatial information
* Role of stride in controlling computation and feature detail
* Understanding object detection pipeline architecture
* Difference between classification and detection tasks

---

## ⚠️ Notes

* Task 2 is a **simplified educational implementation**
* Does not include:

  * Full RPN training
  * mAP evaluation
  * Real detection dataset (uses CIFAR-10 for demonstration)

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 🚀 Future Improvements

* Implement full Faster R-CNN training
* Add mAP and IoU evaluation metrics
* Use real datasets (COCO / Pascal VOC)
* Replace ROI Pooling with ROI Align

---


## ⭐ If you like this project

Give it a ⭐ on GitHub!
