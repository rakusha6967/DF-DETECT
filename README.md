# DEEP DETECT — Synthetic Media & Face Forgery Classifier

**Author:** Lakshya Kumar ([@rakusha6967](https://github.com/rakusha6967))  
**Repository:** [DEEP-DETECT](https://github.com/rakusha6967/DEEP-DETECT)  
**Academic Context:** Class Project Submission  

---

## 📜 Attribution & License Notice

This project is an academic build based on the open-source project [DeepFake-Detect](https://github.com/aaronchong888/DeepFake-Detect) created by **Aaron Chong** and **Hugo Ng**, used under the terms of the **MIT License**.

* **Original Repository:** 
* **Live Reference Demo:** [deepfake-detect.com](https://deepfake-detect.com/)
* **Core Framework:** Python, TensorFlow, Keras, EfficientNet B0, MTCNN.

---

## 🔬 System Overview & Architecture

DEEP DETECT is an end-to-end computer vision pipeline designed to detect deepfake and synthetically manipulated media:

1. **Video Frame Extraction ():** Automatically resizes and extracts individual frames from source mp4/avi videos.
2. **Face Extraction ():** Uses Multi-task Cascaded Convolutional Networks (MTCNN) to detect faces with a 30% bounding box margin.
3. **Dataset Balancing ():** Down-samples majority classes and formats an 80:10:10 split for training, validation, and testing.
4. **CNN Model Training ():** Trains an **EfficientNet B0** neural network (128×128 input, global max pooling, dense ReLU layers, Sigmoid binary classification).

---

## 📊 Performance Metrics

* **Test Accuracy:** 96.36%
* **Precision:** 94.95%
* **Recall:** 97.94%
* **F1-Score:** 96.42%

---

## 📁 Repository Structure



---

## 🚀 Quick Start

### 1. Installation


### 2. Running the Pipeline


---

## 🌐 Web Showcase Deployment

The  folder contains a modern showcase UI. To host via **GitHub Pages**:
1. Navigate to **Settings** → **Pages** in your GitHub repository.
2. Select **Source**:  →  branch →  folder.
3. Save to publish your project website!
