# 🧠 AI-Powered CT Scan Alignment & Lesion Detection

This 12-week research project explores the use of AI and computer vision to assist radiologists in comparing CT scans over time — enabling earlier detection, diagnosis, and tracking of lesions (tissue growth).

---

## 🩺 Project Goal

To automate the comparison of two CT scans taken at different times, by:
- Aligning scan slices for accurate visual comparison
- Detecting and measuring changes in lesions or organs
- Highlighting areas of concern to assist clinical decision-making

---

## 🔬 Key Components

### 1. **Scan Alignment**
- Explored multiple 2D and 3D alignment methods:
  - **Phase correlation** for shift detection
  - **Keypoint-based methods** and **Coherent Point Drift** for non-rigid alignment

### 2. **Lesion Detection & Measurement**
- Developed unsupervised and self-supervised anomaly detection techniques:
  - **Masked data prediction** models
  - **DINO (Vision Transformers)** for tissue segmentation
- Used classical techniques like:
  - **Textons + Mean Shift clustering** for explainable segmentation
  - **3D ellipsoid detection** to locate lesion-like regions

---

## 🛠️ Tools & Methods

- Computer Vision (OpenCV, scikit-image)
- Unsupervised Deep Learning (DINO, masked autoencoders)
- Image Registration Techniques
- Classical ML (Mean Shift, clustering, segmentation)

---

## 📌 Outcome

This project demonstrates a pipeline that can:
- Align CT scans taken on different dates
- Detect visual anomalies in 2D and 3D
- Segment tissue and measure lesion volumes

It aims to reduce the manual effort required by radiologists, while improving consistency in longitudinal imaging comparisons.

---
