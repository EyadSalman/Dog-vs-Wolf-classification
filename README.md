# 🐶🐺 Dog vs Wolf Image Classification

This project tackles the binary classification problem of distinguishing between **dogs** and **wolves** using deep learning. We explore and compare multiple convolutional neural network architectures — from a custom-built **Simple CNN** to powerful **transfer learning models** like **ResNet50**, **EfficientNetB0**, and **MobileNetV2**.

## 📁 Dataset

The dataset consists of two labeled image folders:
Dog_vs_Wolf.zip
├── data/
│   ├── dogs/
│   └── wolves/

Each image belongs to one of the two classes and is cleaned and resized to 150×150 pixels for training.

## 🔍 Project Workflow

### 1. 📦 Data Preparation
- Extract and clean `.zip` dataset
- Remove corrupted images
- Resize and normalize input images
- Perform data augmentation (zoom, flip, shear, etc.)

### 2. 🧠 Models Used
- ✅ Simple CNN (custom Keras model)
- ✅ ResNet50 (frozen pretrained ImageNet weights)
- ✅ EfficientNetB0 (efficient and accurate)
- ✅ MobileNetV2 (lightweight & mobile-optimized)

### 3. 📊 Training & Evaluation
- Accuracy & loss plotted per epoch
- Classification Report: Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- Predict random image from validation set

## 📈 Sample Results

| Model           | Best Val Accuracy | Notes                               |
|------------------|-------------------|--------------------------------------|
| Simple CNN       | ~78–81%           | Best accuracy overall                |
| ResNet50         | ~57–59%           | Low accuracy with small data         |   
| EfficientNetB0   | ~51–53%           | Would be more with more epochs       |         
| MobileNetV2      | ~93–96%           | Slight overfits                      |

## 🖼️ Visualizations

- Random image prediction with label and confidence
- Accuracy & loss over training epochs
- Confusion matrices for each model

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Scikit-learn
- Matplotlib, Seaborn, NumPy
- PIL (Pillow)


