# Brain-Tumor-Detection
# Brain Tumor Detection Using Deep Learning (PyTorch + GUI)

This project is a Brain Tumor Detection System built using PyTorch and a PyQt5 GUI.  
It classifies MRI brain images into tumor categories and provides an easy desktop interface for prediction.
##  Features

###  Model Features
- Trained on MRI brain tumor dataset.
- Uses PyTorch with a CNN / Transfer Learning model.
- Supports tumor categories such as:
  - Glioma
  - Meningioma
  - Pituitary (optional)
  - No Tumor
- Includes:
  - Data preprocessing
  - Augmentation
  - Early stopping
  - Model evaluation (accuracy, loss)

###  GUI Features
- Built using PyQt5.
- Load MRI images directly (.jpg, .png).
- Shows:
  - Image preview
  - Predicted tumor type
- Easy “Load Image” and “Predict” buttons.
##  Project Structure

Brain-Tumor-Detection/
│
├── Brain_tumor_training.ipynb # Model training notebook
├── Brain_tumor_GUI.ipynb # GUI application notebook
├── model/ # Saved model weights (.pth)
├── dataset/ # MRI images dataset
│
└── README.md # Project documentation

