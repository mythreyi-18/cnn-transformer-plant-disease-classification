# Design and Performance Evaluation of a CNN-Transformer Hybrid Model for Plant Disease Classification

## 📌 Project Overview

This project presents a hybrid deep learning model for plant disease classification by combining CNN-based feature extraction with a **Vision Transformer (ViT)**.

The model takes a **plant leaf image as input** and predicts the **corresponding disease name** as the output.

### 🔄 How It Works

**Input:** Plant leaf image 🌿
**Processing:** MobileNetV2 + EfficientNetB0 + Vision Transformer (ViT)
**Output:** Predicted plant disease name 🦠

## 📊 Dataset

The project uses the **PlantVillage dataset**, which contains healthy and diseased plant leaf images belonging to multiple classes.

## 🧠 Model Architecture

The proposed hybrid model uses:

* **MobileNetV2** for CNN-based feature extraction
* **EfficientNetB0** for additional feature extraction
* **Vision Transformer (ViT)** for enhanced feature representation and classification

## 🛠️ Technologies Used

* Python
* TensorFlow & Keras
* Google Colab
* NumPy & Pandas
* Matplotlib
* Scikit-learn
* MobileNetV2
* EfficientNetB0
* Vision Transformer (ViT)

## 📈 Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Specificity
* Cohen's Kappa
* Confusion Matrix
* ROC Curve

The complete implementation, training graphs, confusion matrix, and evaluation results are included in the project notebook.

## Project Type

Final Year Academic Major Project
