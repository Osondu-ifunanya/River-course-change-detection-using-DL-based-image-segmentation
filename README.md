

# River Course Change Detection using Deep Learning-based Image Segmentation (Synthetic Data)

## 📌 Overview

This project applies a **Deep Learning (DL) image segmentation** model to detect changes in river courses using **synthetic multi-temporal satellite imagery**. The approach simulates real-world change detection workflows in hydrology and environmental monitoring.

## 🎯 Objectives

* Simulate multi-temporal satellite imagery for rivers.
* Train a **U-Net segmentation model** to detect changes.
* Identify and map areas where the river’s course has shifted over time.
* Provide a foundation for real-world river change monitoring.

## 🗂 Dataset

* **Type:** Synthetic multi-temporal images
* **Bands:** RGB + simulated water mask
* **Size:** Configurable in code
* **Labels:** Binary masks (changed vs unchanged water pixels)

## ⚙️ Workflow

1. **Synthetic Data Generation**
   Create artificial multi-temporal river images and masks.
2. **Preprocessing**
   Normalize data and prepare it for training.
3. **Model Architecture**
   Use **U-Net** for semantic segmentation.
4. **Training**
   Train the model on synthetic change data.
5. **Evaluation**
   Assess performance using accuracy, IoU, and visualization.
6. **Visualization**
   Compare predicted and ground-truth change maps.

## 🛠 Requirements

```bash
pip install numpy matplotlib tensorflow scikit-learn opencv-python
```

## 🚀 Run

```bash
python river_change_detection.py
```

## 📊 Output

* Accuracy metrics
* Predicted change detection maps
* Side-by-side visual comparison of river course changes

## 📌 Applications

* Riverbank erosion studies
* Floodplain monitoring
* Habitat impact analysis
* Infrastructure risk assessment

