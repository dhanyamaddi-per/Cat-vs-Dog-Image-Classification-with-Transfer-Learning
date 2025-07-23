
# 🐾 Cat vs. Dog Image Classification with Transfer Learning

This project implements a **binary image classifier** to distinguish between cat and dog images using **transfer learning with MobileNetV2**. The model is trained and evaluated using TensorFlow and Keras, with data sourced from local directories in Google Drive.

---

## 🧠 Project Overview

The project utilizes:
- **MobileNetV2** as the base model (pre-trained on ImageNet).
- Custom layers on top for binary classification.
- Data augmentation for improved generalization.
- Performance visualization (accuracy/loss).
- An interactive image selector to display predictions in real time.

---

## 🔬 Research Questions

1. **Can a transfer learning model (MobileNetV2) classify cats vs. dogs with high accuracy using limited compute resources (Google Colab)?**
2. **Does data augmentation improve model generalization and validation accuracy?**
3. **How well can the model distinguish new/unseen images using interactive prediction UI?**

---

## 📈 Key Insights

- Achieved **97%+ accuracy** after 5 epochs with minimal overfitting.
- Validation accuracy reached **100%** in epoch 2, showing effective generalization.
- Data augmentation (rotation, shift, zoom, flip) improved robustness.
- PCA visualization (if applied) showed distinguishable features between classes.
- A simple UI using `ipywidgets` enabled user interaction and visual validation of predictions.

---

## 🧰 Technologies Used

- **TensorFlow & Keras**
- **Transfer Learning (MobileNetV2)**
- **Google Colab**
- **Matplotlib** for plots
- **ipywidgets** for user interaction
- **ImageDataGenerator** for augmentation


---

## 🚀 How to Run the Project

1. Upload the notebook and dataset folders (`train`, `test1`) to your Google Drive.
2. Mount the drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')


