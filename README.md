# Bone_Fractured-or-Not_Fractured-Classification

# Overview
-This project classifies X-ray images into Fractured or Not Fractured using a Convolutional Neural Network (CNN). The dataset consists of 9194 labeled X-ray images downloaded from Kaggle. The model is trained using TensorFlow/Keras with data augmentation to improve generalization.

# Dataset
-The dataset contains 9194 X-ray images categorized into:
     1)Fractured
     2)Not Fractured
-Data is split into Training (80%) and Validation (20%).
-Images are resized to 224×224 for CNN processing.

# Model Architecture
     CNN Layers:
         1)Three Conv2D layers with ReLU activation
         2)MaxPooling2D layers for feature extraction
         3)Flattening & Fully Connected Dense layers
-Final sigmoid activation for binary classification
-Optimizer: Adam
-Loss Function: Binary Crossentropy
-Evaluation Metrics: Accuracy

# Model Performance
-Achieved 96% accuracy on validation data.
-Successfully classifies X-ray images into Fractured or Not Fractured.
-Loss and accuracy plots are provided in results/ directory.

# Results & Visualization
-Confusion Matrix for performance evaluation.
-Grad-CAM visualization to highlight fracture regions in X-ray images.
