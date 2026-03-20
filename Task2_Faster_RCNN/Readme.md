# Task 2: Faster R-CNN Object Detection

This task implements a **simplified Faster R-CNN-style object detection pipeline** to understand the core components and workflow of modern object detection systems.

---

## 📌 Objective

* Understand the architecture of Faster R-CNN
* Implement key components of an object detection pipeline
* Visualize region proposals and detection outputs
* Analyze the difference between classification and detection tasks

---

## ⚙️ Implementation Overview

This project builds a simplified version of Faster R-CNN using TensorFlow/Keras.

### 🔹 Pipeline Components

1. **Backbone CNN**

   * Extracts feature maps from the input image
   * Implemented using a lightweight CNN (VGG-style)

2. **Anchor Generation**

   * Generates multiple bounding boxes (anchors) at each feature map location
   * Uses different scales and aspect ratios

3. **Region Proposal Network (RPN)**

   * Predicts:

     * Objectness score (object vs background)
     * Bounding box refinements

4. **ROI Pooling**

   * Converts variable-sized regions into fixed-size feature maps
   * Ensures compatibility with fully connected layers

5. **Detection Head**

   * Classifies objects
   * Refines bounding boxes

---

## 📊 Dataset

* **CIFAR-10**

  * Used for demonstration purposes
  * Does not contain bounding box annotations
  * Helps in understanding pipeline flow

---

## 🔍 Features

* Anchor box visualization
* Region proposal visualization
* End-to-end detection pipeline
* Backbone training for better feature extraction

---

## ⚠️ Limitations

This is a **simplified educational implementation** and does not include:

* Full RPN training
* Detection head training with bounding box labels
* IoU (Intersection over Union) calculation
* mAP (Mean Average Precision) evaluation
* Real object detection dataset (e.g., COCO, Pascal VOC)

---

## 🧠 Key Learnings

* Understanding of two-stage object detection
* Role of RPN in replacing selective search
* Importance of ROI pooling in standardizing inputs
* Difference between classification and object detection

---

## 🧠 Conclusion

This implementation successfully demonstrates the **core architecture and workflow of Faster R-CNN**.

* The pipeline structure is correct and modular
* Feature extraction improves after training the backbone
* However, without proper training and evaluation, detection results are not accurate

This project provides a strong foundation for building a complete object detection system using real datasets and evaluation metrics.

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
