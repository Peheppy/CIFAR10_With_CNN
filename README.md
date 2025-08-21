# Image Classification on CIFAR-10 with PyTorch

This project implements a complete **Deep Learning training and evaluation pipeline** (ResNet-18 and VGG-19) for image classification on the **CIFAR-10** dataset.  
The code was developed in **Google Colab** using the **PyTorch** library.

---

## 📂 Project Structure

- **Preprocessing & Transformations**
  - Data augmentation (horizontal flip, color jitter, random rotation).
  - Normalization using ImageNet statistics.
  - Properly split training, validation, and test sets.

- **Implemented Models**
  - `ResNet18` with pretrained ImageNet weights.
  - `VGG19` adapted for CIFAR-10.

- **Training**
  - Optimizer: **Adam**
  - Learning rate scheduler: **CosineAnnealingLR**
  - Loss function: **CrossEntropyLoss**
  - Strategies: **early stopping** and **gradient clipping**.

- **Evaluation**
  - Metrics: Accuracy, Balanced Accuracy, Precision, Recall, F1-score.
  - Visualizations: Loss/accuracy curves, sample predictions, and confusion matrix.
