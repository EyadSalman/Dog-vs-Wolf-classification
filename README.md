# 🐶🐺 Dog vs Wolf Image Classification

This project tackles the binary classification problem of distinguishing between **dogs** and **wolves** using deep learning. We explore and compare multiple convolutional neural network architectures — from a custom-built **Simple CNN** to powerful **transfer learning models** like **ResNet50**, **EfficientNetB0**, and **MobileNetV2**.

---

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

---

## 📈 Sample Results

| Model           | Best Val Accuracy | Notes                                 |
|----------------|-------------------|----------------------------------------|
| Simple CNN      | ~78–81%           | Solid baseline                         |
| ResNet50        | ~57–59%           | Struggled with small data              |
| EfficientNetB0  | ~51–53%           | Potential for improvement with epochs  |
| MobileNetV2     | ~93–96%           | High accuracy, slight overfitting      |

---

## 🖼️ Visualizations

- 🔍 Random image predictions with actual and predicted labels
- 📈 Accuracy & loss curves for training and validation
- 📊 Confusion matrices to evaluate model performance

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy, Matplotlib, Seaborn
- PIL (Pillow)

---

## 📂 Project Structure

The dataset consists of images divided into two categories — `dogs` and `wolves`. The directory structure after unzipping is:

```plaintext
Dog_vs_Wolf.zip
├── data/
│   ├── dogs/
│   └── wolves/
