# 🌱 Plant Disease Detection System for Solanaceous Vegetables

## 🚀 Project Overview
The **Plant Disease Detection System** is a deep learning-based solution designed to automatically detect diseases in Solanaceous vegetable crops such as **tomatoes, potatoes, peppers, and eggplants**. Using **image analysis** and **Convolutional Neural Networks (CNNs)**, the system enables early disease detection, helping farmers take timely interventions and improve crop yield.

---

## ✨ Features
- **🩺 Automatic Disease Detection:** Detects **15 different disease classes** from leaf images.  
- **🤖 Deep Learning Models:** Utilizes **VGG16** and **ResNet** CNN architectures for robust feature extraction.  
- **📊 High Accuracy:** Achieved **Training Accuracy: 96.85%** and **Validation Accuracy: 96.67%**, with minimal overfitting.  
- **⚡ Efficient Training:** Preprocessed images to **128x128 RGB** and used **batch size 32** for efficient training.  
- **📈 Performance Evaluation:** Confusion matrices and validation metrics assess model performance.  
- **🌐 User-Friendly Interface:** Optionally includes a web interface to upload images and receive disease predictions.

---

## 🗂 Dataset
- Leaf images of **Solanaceous crops** representing **15 disease categories**.  
- Preprocessed to **128x128 RGB** format to standardize inputs.  
- Split into **training and validation sets** to ensure robust evaluation.
- The accuracy acheived is 96.67%

---

## 🏗 Model Architecture

### VGG16
- Pre-trained CNN fine-tuned for disease classification.  
- Consists of **convolutional layers**, **max pooling**, and **fully connected layers**.

### ResNet
- Deep residual network to handle **vanishing gradient problems**.  
- Improves feature extraction for **complex leaf patterns**.

Both models were trained using **categorical cross-entropy loss** and **Adam optimizer**.

---

## ⚙️ Installation

1. Clone the repository:  
```bash
git clone <repository-url>
cd PlantDiseaseDetectionProject
