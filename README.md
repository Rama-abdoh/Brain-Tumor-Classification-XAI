# Brain-Tumor-Classification-XAI
# Brain Tumor Classification with Explainable AI (Grad-CAM)

This project explores CNN-based brain tumor classification using MRI images and applies Explainable AI techniques to interpret model decisions.

## Project Structure
- Simple CNN model
- Simpler residual CNN model
- Advanced CNN model
- Grad-CAM analysis for explainability

## Dataset
BRISC brain tumor MRI dataset (glioma, meningioma, no_tumor, pituitary).
BRISC Dataset link :https://zenodo.org/records/17524350

## Methods
- Data augmentation and class balancing
- CNN and residual architectures built from scratch
- Grad-CAM for visual explanations
- Analysis of correct and incorrect predictions

## Key Findings
- Correct predictions focus mainly on tumor regions
- Incorrect predictions often rely on background structures
- Grad-CAM reveals model weaknesses not visible from accuracy alone

## Technologies
Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib

## Author
Rama Abdoh
