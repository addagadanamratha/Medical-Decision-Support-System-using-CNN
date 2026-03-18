# 🧠 Medical Decision Support System for Stroke Prediction using CNNs

## 📌 Overview

This project presents a **deep learning-based medical decision support system** for detecting brain stroke from CT scan images. The system leverages **Convolutional Neural Networks (CNNs)** along with **OpenCV-based image preprocessing** to enable accurate and efficient stroke classification.

The goal is to assist healthcare professionals by providing **fast, reliable, and automated stroke detection**, reducing diagnostic delays and improving patient outcomes.

---

## 🚀 Key Features

* CNN-based classification of CT scan images (Stroke vs Normal)
* Achieved **~95% accuracy** with strong precision and recall
* Integrated **OpenCV (CV2) preprocessing pipeline**
* Comparative evaluation with traditional ML models (Decision Tree, Random Forest)
* Real-time prediction through a **Django-based web interface**
* Feature-level visualization highlighting clinically relevant regions

---

## 🛠️ Tech Stack

* **Programming:** Python
* **Deep Learning:** TensorFlow, Keras
* **Image Processing:** OpenCV (CV2)
* **Machine Learning:** Scikit-learn
* **Web Framework:** Django
* **Data Handling:** NumPy, Pandas

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Image resizing and normalization
* Noise reduction using Gaussian filtering
* Contrast enhancement (CLAHE / Histogram Equalization)
* Edge detection for structural feature highlighting

### 2. Model Development

* Designed a **CNN architecture** with:

  * Convolutional layers (feature extraction)
  * Max pooling layers (dimensionality reduction)
  * Fully connected layers (classification)
* Used **Adam optimizer** and **cross-entropy loss**
* Trained over multiple epochs with stable convergence

### 3. Model Evaluation

* Accuracy: **~95%**
* Precision: **~95%**
* Recall: **~94%**
* F1-Score: **~94%**
* Confusion matrix analysis showed low false positives and false negatives

### 4. Comparative Analysis

* Decision Tree: ~93% accuracy
* Random Forest: ~94% accuracy
* CNN outperformed traditional models due to better spatial feature learning

---

## 📊 Results

* Successfully classified stroke and non-stroke CT scans with high reliability
* Strong generalization across test data
* Effective detection of subtle stroke patterns such as:

  * Lesion boundaries
  * Brain asymmetry
  * Intensity variations

---

## 🌐 Web Application

A **Django-based interface** allows users to:

* Upload CT scan images
* Receive real-time stroke predictions
* View results instantly

This demonstrates practical deployment of the model in real-world scenarios.

---

## ⚠️ Note

* Dataset sourced from Kaggle (not included due to size constraints)
* Trained model files are excluded to keep the repository lightweight

---

## 🔮 Future Improvements

* Integration of **transfer learning / transformer-based models**
* Use of **Explainable AI (XAI)** for better interpretability
* Deployment in real-time clinical environments
* Integration with multimodal patient data
