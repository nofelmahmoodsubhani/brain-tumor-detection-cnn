# Brain Tumor Detection Using Deep Learning

A deep learning project that classifies brain MRI images into tumor categories using transfer learning and a Convolutional Neural Network (CNN) architecture.

## Overview

This project uses **VGG16 with a Convolutional Block Attention Module (CBAM)** to classify brain MRI images. It combines a pretrained model with an attention mechanism to help the network focus on relevant image features.

The project includes image preprocessing, data augmentation, model training, performance evaluation, and an interactive interface built with Gradio.

## Model Architecture

- **Base model:** VGG16 pretrained on ImageNet
- **Attention mechanism:** Convolutional Block Attention Module (CBAM)
- **Framework:** TensorFlow / Keras
- **Interface:** Gradio

## Dataset

The project uses brain MRI image datasets available on Kaggle:

1. [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
2. [Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)

Download the datasets from the links above and configure the dataset paths according to the notebook.

**Note:** The datasets are not included in this repository because of their size.

## Reported Results

The notebook reports the following test-set results:

| Metric | Reported Result |
|---|---:|
| Test Accuracy | 99% |
| Precision | 99% |
| Recall | 99% |
| F1-Score | 99% |

These figures are the results reported in the notebook and have not been independently reproduced.

## Features

- Transfer learning using VGG16
- CBAM attention mechanism
- Image preprocessing and augmentation
- Model training and evaluation
- Confusion matrix visualization
- Performance metric reporting
- Interactive MRI image classification through Gradio

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Gradio

## Getting Started

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd brain-tumor-detection-cnn
```

### 2. Install Dependencies

```bash
pip install tensorflow numpy matplotlib scikit-learn gradio jupyter
```

### 3. Download the Dataset

Download the datasets from the Kaggle links above and extract them locally.

### 4. Run the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `brain_tumor_detection.ipynb` and follow the notebook cells to run the project.

## Disclaimer

This project is intended for educational and research purposes only. It is not a clinically validated diagnostic tool and must not be used as a substitute for professional medical evaluation.

## Author

Developed as a deep learning project exploring brain MRI image classification, transfer learning, and attention mechanisms.
