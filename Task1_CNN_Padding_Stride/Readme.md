# Task 1: CNN Padding & Stride Analysis

This task focuses on analyzing the impact of **padding** and **stride** in Convolutional Neural Networks (CNNs) and how these hyperparameters affect model performance, feature extraction, and computational efficiency.

---

## 📌 Objective

* Understand how padding (`same` vs `valid`) influences spatial dimensions and feature preservation
* Analyze the effect of different stride values on computation and accuracy
* Evaluate trade-offs between performance and efficiency in CNN design

---

## ⚙️ Experiment Setup

* **Dataset:** MNIST (grayscale image classification)
* **Framework:** TensorFlow / Keras
* **Model:** Custom CNN with configurable padding and stride

### Configurations Tested:

* Padding:

  * `same`
  * `valid`
* Strides:

  * (1,1), (2,2), (3,3)

---

## 🧠 Key Concepts

### 🔹 Padding

* **Same Padding:** Preserves input dimensions
* **Valid Padding:** No padding → reduces output size

### 🔹 Stride

* Controls step size of convolution
* Larger stride → faster computation but loss of detail

---

## 📊 Evaluation Metrics

* Model Accuracy
* Training Time
* Number of Parameters

---

## 📈 Results Summary

* **Same padding** provides better accuracy by preserving edge information
* **Valid padding** reduces computation but may lose important features
* **Higher stride values** improve efficiency but reduce model performance
* Best performance observed with:

  * `same` padding + stride (1,1)

---

## 🔍 Visualization

* Feature map activations
* Accuracy & loss curves
* Comparison charts for parameters and training time

---

## 🧠 Conclusion

This experiment demonstrates that CNN design involves a trade-off between **accuracy and efficiency**.

* Preserving spatial information (via padding) improves feature learning
* Reducing computation (via stride) speeds up training but may degrade accuracy

The optimal configuration depends on the application requirements, such as real-time processing vs high precision tasks.

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

