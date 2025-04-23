# Brain Tumor Segmentation using U-Net in TensorFlow

This project implements a deep learning-based semantic segmentation model to identify and segment brain tumors from MRI scans. Using a U-Net architecture, the model learns to distinguish tumor regions from the background in medical images.

---

## 🧠 Project Overview

- **Goal**: Accurately segment tumor regions from brain MRI images using deep learning.
- **Dataset**: Brain tumor segmentation dataset with paired images and masks.
- **Architecture**: U-Net convolutional neural network implemented in TensorFlow/Keras.
- **Platform**: Developed locally in VS Code with GPU support.

---

## 🚀 Technologies Used

- **TensorFlow / Keras** – For building and training the deep learning model.
- **OpenCV** – For image processing and data preparation.
- **Scikit-learn** – For evaluation metrics and model validation.
- **Matplotlib / Seaborn** – For visualization of training progress and results.

---

## 📊 Model Evaluation

The model was trained for 10 epochs and evaluated on a held-out test set.

| Metric              | Value    |
|---------------------|----------|
| **Accuracy**        | 98.27%   |
| **Precision**       | 0.5591   |
| **Recall**          | 0.7076   |
| **F1 Score**        | 0.6247   |
| **AUC-ROC Score**   | 0.8492   |

### 📌 Confusion Matrix

|                    | Predicted Negative | Predicted Positive |
|--------------------|--------------------|--------------------|
| **Actual Negative**| 39,150,709         | 366,303            |
| **Actual Positive**| 191,962            | 464,594            |

