# Deforestation Mapping in Dhaka – Semantic Segmentation

## Overview
Rapid urbanization and industrialization in Dhaka, Bangladesh have caused significant changes in land use, leading to widespread deforestation and loss of ecosystem services. Accurate monitoring of these changes is crucial for sustainable urban planning and environmental conservation.  

This project builds a high-resolution satellite imagery dataset of Dhaka (2012–2022) and applies deep learning models for semantic segmentation to detect deforested areas. We compare the performance of standard U-Net, Attention U-Net, and a hybrid ResNet50-Attention U-Net model.

---

## Features
- **High-resolution dataset**: Satellite imagery spanning 2012–2022.
- **Comparative analysis**: Evaluates multiple deep learning models for semantic segmentation.
- **Advanced models**: Incorporates Attention U-Net and ResNet50-Attention U-Net.
- **Metrics-based evaluation**: Performance assessed with Dice Score, IoU, F1-Score, Precision, and Recall.
- **Urban-forest boundary detection**: Handles complex urban-forest transitions effectively.

---

## Tech Stack
- **Language**: Python
- **Deep Learning Frameworks**: TensorFlow, Keras, PyTorch
- **Libraries**: NumPy, OpenCV, scikit-learn, matplotlib
- **Models Implemented**: U-Net, Attention U-Net, ResNet50-Attention U-Net
- **Data**: High-resolution satellite imagery of Dhaka

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/aman0311x/dhaka-deforestation.git
cd dhaka-deforestation
