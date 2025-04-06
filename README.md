# 🌸 102 Flower Category Classification

This project is classification of images into 102 different flower species using a deep learning model. It use the **102 Category Flower Dataset** curated by Maria-Elena Nilsback and Andrew Zisserman at Oxford's Visual Geometry Group.

---

## 📁 Dataset Overview

- **Name**: 102 Category Flower Dataset
- **Total Categories**: 102
- **Images per Category**: 40 to 258
- **Source**: [Oxford VGG](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/)
- **Variations**: Scale, lighting, pose, and intra-class variation

Due to size constraints, the dataset is not included in this repository. You can manually download it from the official site linked above.

---

## 🚀 Project Structure

- `cv.ipynb`: The full notebook containing data loading, visualization, training, and evaluation.
- `results/image.png`: Visualizations of training vs. validation loss and accuracy over epochs.

---

## 🧠 Model Summary

- Framework: PyTorch / TensorFlow (mention the actual one used)
- Layers: [Add brief about the model – e.g., Pretrained ResNet50 + custom FC layers]
- Loss: CrossEntropyLoss
- Optimizer: Adam
- Metrics: Accuracy

---

## 📈 Results

Here’s the training progress for the initial experiment:

- ✅ Accuracy (Validation): **~84%**
- 📉 Loss is steadily decreasing, indicating good convergence
- Minor overfitting observed; data augmentation & dropout are next steps

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/flower-classification.git
   cd flower-classification
