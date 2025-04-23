# 🧠 Brain Tumor Detector

A MATLAB-based GUI application for detecting brain tumors from MRI images using image processing techniques such as median filtering, edge detection, and binary segmentation.

## 📋 Table of Contents

- [Overview](#-overview)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Working](#-working)
- [Features](#-features)
- [License](#-license)


---

## 🧠 Overview

This project provides a graphical user interface (GUI) in MATLAB to detect brain tumors from MRI scans. It utilizes common image processing techniques like grayscale conversion, noise reduction with median filtering, edge detection using the Sobel operator, and segmentation to highlight tumor-affected regions.

---

## 📦 Prerequisites

Before running the application, ensure you have the following installed:

- **MATLAB R2016b or later**
- Image Processing Toolbox
- GUIDE (MATLAB's GUI Development Environment)

---

## 🛠️ Installation

1. **Clone or download this repository.**
2. **Open MATLAB.**
3. **Run the GUI file using the command:**

   ```matlab
   run('Brain_Tumor_Detector.fig')

## ▶️ Working
The GUI workflow involves four main steps:

## 🖼️ Select Image
Click "Select Image" button to upload an MRI brain scan.

The uploaded image is displayed on the interface.

## 🧹 Median Filtering
Click "Median Filtering" to reduce noise using a median filter.

The result is shown on the second display panel.

## ✏️ Edge Detection
Click "Edge Detection" to apply Sobel operators in both X and Y directions.

The result highlights potential tumor boundaries.

## 🎯 Tumor Detection
Click "Tumor Detection" to:

Convert the image to binary format

Label connected regions

Identify the region with maximum area and high solidity

Apply dilation for enhancement

Outline the detected tumor in yellow

The result is shown on the fourth panel.

## ✨ Features
✅ GUI-based, beginner-friendly

✅ Works with grayscale and RGB MRI scans

✅ Uses classical image processing (no ML required)

✅ Tumor boundary clearly marked

✅ Real-time image preview at each stage

## 📄 License

You are free to:

Use the software for personal, academic, or commercial purposes

Modify and distribute the code with proper attribution
