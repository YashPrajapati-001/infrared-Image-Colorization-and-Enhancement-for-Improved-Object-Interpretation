# 🌍 Infrared Image Colorization and Enhancement for Improved Object Interpretation

## 📌 Overview

This project presents an AI-powered framework for enhancing and colorizing infrared (IR) satellite images to improve object interpretation during night-time and adverse weather conditions.

The system performs:

* Super-Resolution and Image Enhancement
* IR → RGB Colorization
* Semantic Preservation
* Improved Object Detection and Segmentation

---

## 🚀 Problem Statement

Infrared satellite images are inherently:

* Monochrome
* Low in contrast
* Lacking semantic textures

These limitations make it difficult for analysts and computer vision models to identify:

* Buildings
* Roads
* Vehicles
* Vegetation
* Water Bodies

This project transforms low-visibility IR images into high-fidelity, colorized RGB representations.

---

## 🏗️ System Architecture

```text
Landsat 8/9 IR Images
          ↓
Data Preprocessing & Co-registration
          ↓
IR Super-Resolution Module
          ↓
Semantic Segmentation Module
          ↓
GAN-based IR → RGB Colorization
          ↓
Enhanced Colorized RGB Image
          ↓
Object Detection & Interpretation
```

---

## ✨ Features

* High-resolution enhancement of IR imagery
* Realistic RGB color generation
* Semantic integrity preservation
* Artifact reduction
* Better object detection performance
* Scalable for disaster management and surveillance applications

---

## 🛠️ Tech Stack

* Python
* PyTorch / TensorFlow
* OpenCV
* Rasterio
* GDAL
* CycleGAN / Pix2Pix / ESRGAN
* Landsat 8/9 Dataset (USGS)

---

## 📊 Evaluation Metrics

* PSNR (Peak Signal-to-Noise Ratio)
* SSIM (Structural Similarity Index)
* FID (Fréchet Inception Distance)
* Inference Time

---

## 🌐 Applications

* Disaster Management
* Environmental Monitoring
* Night-time Surveillance
* Smart Agriculture
* Border Security
* Remote Sensing Analytics

---

## 📈 Future Scope

* Real-time satellite image enhancement
* Integration with object detection models (YOLO, Mask R-CNN)
* Multi-spectral and hyperspectral image translation
* Cloud deployment for large-scale processing

---

## 👨‍💻 Author

**Yash Prajapati**

If you like this project, consider giving it a ⭐ on GitHub.
