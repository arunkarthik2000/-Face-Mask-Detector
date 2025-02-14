# Face Mask Detector using Convolutional Neural Networks  

## Overview  
The **Face Mask Detector** is a real-time deep learning-based application designed to identify individuals **wearing** or **not wearing** face masks. Built using **Convolutional Neural Networks (CNNs)**, this project is implemented with **Python, TensorFlow, and OpenCV** for efficient detection in images and live video streams.  

This system can be seamlessly integrated with:  
- **PC webcams** for real-time personal monitoring.  
- **CCTV systems** for public space compliance monitoring.  

## Features  
- **Real-Time Face Mask Detection** using a trained deep learning model.  
- **Webcam Integration** to analyze live video feeds.  
- **CNN-Based Model** for high-accuracy classification of masked and unmasked faces.  
- **OpenCV-Powered Face Detection** before classification.  
- **Lightweight & Scalable** for broader deployment in surveillance systems.  
- **Cross-Platform Compatibility** for Windows, macOS, and Linux.  

## Tech Stack  

### Software  
- **Python 3.x** – Core programming language.  
- **TensorFlow & Keras** – Used to build and train the CNN model.  
- **OpenCV** – Facilitates real-time face detection.  
- **NumPy & Pandas** – Used for data preprocessing and handling.  
- **Matplotlib & Seaborn** – Used for visualizing model performance and dataset statistics.  

### Hardware Requirements  
- **PC/Laptop with Webcam** (for real-time detection).  
- **GPU (Optional)** – Recommended for faster model inference.  

## Working Principle  

1. **Face Detection**  
   - OpenCV detects faces from images or video frames.  
2. **Image Preprocessing**  
   - Extracted faces are resized, normalized, and fed into the trained **CNN model**.  
3. **Mask Classification**  
   - The CNN model classifies the detected face as either:  
     - **"Mask"** (Face Mask Detected)  
     - **"No Mask"** (No Face Mask)  
4. **Real-Time Display**  
   - The detected face is highlighted, and an appropriate **label and bounding box** are displayed.  

## Dataset  
The model is trained on a dataset consisting of:  

- **Masked Faces** – Images of people wearing masks.  
- **Unmasked Faces** – Images of people without masks.  

### Data Preprocessing  
- **Image Augmentation** to improve generalization.  
- **Normalization & Resizing** for efficient model input.  

## Future Enhancements  
- **Multi-Face Detection** – Detect multiple faces within a single frame.  
- **Mobile Integration** – Deploy as a mobile app for on-the-go detection.  
- **Cloud-Based Monitoring** – Enable remote mask compliance analysis.  
- **Edge AI Optimization** – Deploy on Raspberry Pi or Jetson Nano for IoT-based real-time detection.  

## Conclusion  
The **Face Mask Detector** provides an **automated, real-time** solution for mask compliance monitoring using **deep learning and computer vision**. It can be deployed in **public places, offices, hospitals, and commercial spaces** to ensure safety and prevent the spread of airborne diseases.  
