# Facial-Recognition

# Image Classification and Face Detection Project

This repository contains files related to an image classification and face detection system. Below is an overview of the included files and their purposes.

## 📁 Repository Structure

| File/Folder                  | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| `Image classification (practice)-2.ipynb` | Jupyter Notebook containing image classification practice code.             |
| `best_trained_model.pkl`     | Pretrained model file for image classification/face detection.              |
| `haarcascade_eye.xml`        | Haar Cascade classifier file for eye detection.                             |
| `haarcascade_frontalface.xml`| Haar Cascade classifier file for frontal face detection.                    |
| `number_person_file.json`    | JSON file containing data about numbers/persons (likely for classification).|
| `README.md`                  | Project documentation (this file).                                          |

## Quick Start

1. **Prerequisites**:
   - Python 3.x
   - OpenCV (for Haar Cascade files)
   - Jupyter Notebook (to run the practice file)

2. **Usage**:
   - Run the Jupyter Notebook `Image classification (practice)-2.ipynb` to explore the image classification implementation.
   - Use the `.pkl` model file for predictions in your application.
   - The Haar Cascade XML files can be used with OpenCV for real-time face/eye detection.

## 🛠️ Dependencies

Install required packages:
```bash
pip install opencv-python numpy pandas scikit-learn jupyter
