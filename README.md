# CNN-DL_AI_pythonproject
Pneumonia Detection using Convolutional Neural Network (CNN)
Project Overview
This project presents a Deep Learning-based Pneumonia Detection System using a Convolutional Neural Network (CNN). The model is trained to classify chest X-ray images into two categories:

Normal
Pneumonia

The goal is to assist in the early detection of pneumonia through automated medical image classification.

About the Project
Pneumonia is a serious lung infection that can be life-threatening if not diagnosed early. Manual analysis of chest X-ray images requires experienced radiologists and can be time-consuming.
This project applies a Convolutional Neural Network (CNN) to automatically learn image features and accurately classify chest X-ray images.

The complete workflow includes:

Data preprocessing
Data augmentation
CNN model development
Model training
Performance evaluation
Prediction on unseen test images

Features
Chest X-ray image classification
Custom CNN architecture
Image preprocessing and normalization
Data augmentation using ImageDataGenerator
EarlyStopping to reduce overfitting
Model evaluation using multiple metrics
Confusion Matrix visualization
Classification Report
Training and Validation Accuracy/Loss graphs

Technologies Used
Python
TensorFlow
Keras
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook

Dataset Structure
dataset/

├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
│
├── test/
│   ├── NORMAL/
│   └── PNEUMONIA/
CNN Architecture
The CNN model consists of:

Conv2D Layers
Batch Normalization
MaxPooling Layers
Dropout Layers
Flatten Layer
Dense Hidden Layer
Sigmoid Output Layer

The model performs binary classification between:

NORMAL
PNEUMONIA

Training Configuration
Parameter	Value
Image Size	150 × 150
Batch Size	32
Epochs	10
Optimizer	Adam
Loss Function	Binary Crossentropy
Activation	ReLU & Sigmoid

Model Evaluation
The model performance is evaluated using:

Training Accuracy
Validation Accuracy
Training Loss
Validation Loss
Test Accuracy
Confusion Matrix
Classification Report
Prediction Visualization

Workflow
Chest X-ray Images
        │
        ▼
Data Preprocessing
        │
        ▼
Data Augmentation
        │
        ▼
CNN Model
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Prediction
How to Run
Clone this repository
git clone https://github.com/yourusername/Pneumonia-Detection-CNN.git
Open the notebook
Pneumonia_Detection_CNN_PROJECT(Binshah_Joseph_).ipynb
Install the required libraries
pip install tensorflow numpy matplotlib scikit-learn
Download the Chest X-ray dataset.
Update the dataset path in the notebook.
Run all notebook cells.

Output

The notebook generates:

Model Summary
Training Accuracy Graph
Validation Accuracy Graph
Loss Curves
Confusion Matrix
Classification Report
Sample Predictions

Future Improvements
Increase the dataset size
Apply Transfer Learning (ResNet50, EfficientNet, MobileNetV2)
Hyperparameter tuning
Deploy the model using Streamlit or Flask
Convert the project into a web application

Author
Binshah Joseph
BS Computer Science
Deep Learning | Computer Vision | Machine Learning

 License
This project is developed for educational and learning purposes.
