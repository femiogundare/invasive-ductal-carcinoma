# Invasive Ductal Carcinoma Classification using Deep Learning

Invasive ductal carcinoma (IDC) is the most common type of breast cancer, accounting for a large proportion of invasive breast cancer cases worldwide. IDC begins in the milk ducts of the breast and spreads into surrounding breast tissue. If not detected and treated early, it can spread to lymph nodes and other parts of the body.

Histopathological examination remains the standard method for diagnosing IDC. Pathologists analyze stained breast tissue slides under a microscope to identify cancerous cells and determine tumor characteristics. However, manual analysis of histopathology images can be time-consuming and may vary depending on clinical experience and workload.

Recent advances in artificial intelligence, computer vision, and deep learning have created new opportunities for automated cancer detection from medical images. Convolutional neural networks (CNNs) and transfer learning approaches have shown strong performance in histopathology image classification tasks, including breast cancer detection. These models can learn complex visual patterns from tissue images and assist in distinguishing invasive carcinoma from normal tissue regions.

This project explores the application of deep learning techniques for invasive ductal carcinoma classification using histopathology image data.

## Repository Structure

```text
invasive-ductal-carcinoma/
│
├── config/                   # Configurations
├── output/                   # Outputs
├── predictions/              # Predictions
├── result/                   # Results
├── utilities/                # Utilities
├── build_idc_dataset.py      # Build data in HDF5 format
├── ensemble.py               # Ensemble learning
└── notebook.ipynb            # Jupyter notebooks for experiments and EDA
├── predict.py                # Inference script
└── train_model.py            # Training script
```

## Methodology

### 1. Data Preprocessing

- Image resizing
- Normalization
- Data cleaning
- Train/validation/test split
- Handling class imbalance

### 2. Data Augmentation

- Rotation
- Horizontal and vertical flipping
- Zooming
- Random cropping
- Brightness adjustments

### 3. Model Development

- Custom CNN
- ResNet
- EfficientNet
- DenseNet
- Transfer learning models

### 4. Training

- Binary cross-entropy loss
- Adam optimizer
- Learning rate scheduling
- Early stopping
- Model checkpointing

### 5. Evaluation

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix


## Technologies Used

- Python
- PyTorch / TensorFlow
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- Jupyter Notebook

