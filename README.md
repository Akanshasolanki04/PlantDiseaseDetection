Plant Disease Detection System for Solanaceous Vegetables 🌱

###Project Overview
The Plant Disease Detection System is a deep learning-based solution designed to automatically detect diseases in Solanaceous vegetable crops (like tomatoes, potatoes, peppers, and eggplants). By leveraging image analysis and convolutional neural networks (CNNs), the system enables early disease detection, helping farmers take timely interventions and improve crop yield.

###Features

Automatic Disease Detection: Detects 15 different disease classes from leaf images.

Deep Learning Models: Utilizes VGG16 and ResNet CNN architectures for robust feature extraction.

High Accuracy: Achieved Training Accuracy: 96.85% and Validation Accuracy: 96.67%, with minimal overfitting.

Efficient Training: Preprocessed images to 128x128 RGB and used batch size of 32 for efficient model training.

Performance Evaluation: Confusion matrices and validation metrics used to assess model performance.

User-Friendly Interface: Optionally includes a web interface to upload images and receive disease predictions.

###Dataset

Collected leaf images of Solanaceous crops representing 15 disease categories.

Images were preprocessed to 128x128 RGB format to standardize inputs for CNN models.

Dataset split into training and validation sets to ensure robust model evaluation.

###Model Architecture

VGG16

Pre-trained CNN model fine-tuned for disease classification.

Utilizes convolutional layers, max pooling, and fully connected layers.

ResNet

Deep residual network to handle vanishing gradient problems in deep networks.

Improves feature extraction for complex leaf patterns.

Both models were trained using categorical cross-entropy loss and Adam optimizer.

###Installation

Clone the repository:

git clone <repository-url>
cd PlantDiseaseDetectionProject

###Results

Training Accuracy: 96.85%

Validation Accuracy: 96.67%

Confusion matrices confirm minimal misclassifications between disease classes.

###Technologies Used

Python

TensorFlow / Keras

CNN Models: VGG16, ResNet

OpenCV / PIL for image processing

Matplotlib / Seaborn for evaluation plots

 HTML, CSS, JavaScript for frontend

###Future Work

Expand dataset with more crops and disease categories.

Implement real-time detection using mobile or drone images.

Integrate with agricultural advisory systems for automated alerts.

Improve model efficiency for edge deployment.

