# Brain Tumor Detection (PyTorch + GUI)

CNN-based brain tumor classification system using PyTorch, trained on MRI scans, with a PyQt5 desktop GUI for real-time prediction.  
This repository contains the full pipeline: data preprocessing, model training, inference, and a GUI demo.

## Files
- **Brain_tumor_training.ipynb** — Jupyter notebook for model training (dataset loading, augmentation, CNN training, evaluation).
- **Brain_tumor_GUI.ipynb** — GUI notebook (PyQt5 interface for loading MRI images and predicting tumor type).
- **model/** — folder containing trained model weights (`.pth` file).
- **requirements.txt** — Python dependencies.

## Quickstart (Google Colab / Local Machine)
1. Open `Brain_tumor_training.ipynb` or `Brain_tumor_GUI.ipynb` in Jupyter.
2. Install dependencies:
3. Run training notebook (optional).  
4. Open GUI notebook:
- Run all cells  
- Desktop app appears  
- Load MRI → Predict tumor type (Glioma / Meningioma / Pituitary / No Tumor)

## Notes
- Dataset is **not included**. Please download a public MRI dataset (e.g., Kaggle Brain Tumor MRI Dataset).
- Ensure model weights (`.pth`) are placed in the `model/` folder before running GUI.
- GUI is implemented using **PyQt5** and uses the trained PyTorch model for inference.

## Contact
**Aditya Kumar Maurya**  
Email: alok2371354@gmail.com  
LinkedIn: www.linkedin.com/in/adityakmaurya  
