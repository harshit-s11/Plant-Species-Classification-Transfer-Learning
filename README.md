# House Plant Species Classification using Transfer Learning

A deep learning-based image classification system that identifies different species of house plants from images using transfer learning. The project leverages TensorFlow and Keras to build, train, fine-tune, and evaluate a convolutional neural network capable of accurately classifying plant species.

---

## Overview

This project demonstrates an end-to-end deep learning workflow for image classification. It includes data preprocessing, dataset cleaning, model training, fine-tuning, evaluation, and prediction using a pretrained convolutional neural network.

The model is trained on a dataset containing images of various house plant species and predicts the species of an input plant image.

---

## Features

- Dataset cleaning and preprocessing
- Automatic train, validation, and test dataset creation
- Data augmentation for improved generalization
- Transfer learning using a pretrained CNN
- Fine-tuning of the pretrained model
- Performance evaluation using accuracy and loss metrics
- Prediction on unseen plant images
- Visualization of training history

---

## Technologies Used

- Python
- Jupyter Notebook
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```
House-Plant-Species-Classification/
│
├── model-final.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Dataset

The project uses a dataset containing images of different house plant species.

Each plant species is stored in a separate folder, allowing TensorFlow to automatically assign class labels during training.

Dataset preprocessing includes:

- Removing corrupted images
- Splitting data into training, validation, and testing sets
- Data augmentation to improve model robustness

---

## Model Architecture

The project uses Transfer Learning with a pretrained Convolutional Neural Network (CNN).

The workflow is:

```
Input Image
      │
      ▼
Pretrained CNN
      │
      ▼
Global Average Pooling
      │
      ▼
Dropout Layer
      │
      ▼
Dense Softmax Layer
      │
      ▼
Predicted Plant Species
```

After initial training, selected layers of the pretrained model are fine-tuned to improve classification performance.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/ans-jain/House-Plant-Species-Classification.git
```

Move into the project directory:

```bash
cd House-Plant-Species-Classification
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
model-final.ipynb
```

---

## Running the Project

1. Download the plant species dataset.
2. Update the dataset path in the notebook.
3. Run all notebook cells.
4. Train the model.
5. Evaluate the model.
6. Predict the species of new plant images.

---

## Results

The notebook provides:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Model Evaluation
- Plant Species Prediction

---

## Applications

- Smart Gardening
- Plant Identification
- Botanical Research
- Educational Projects
- Computer Vision
- Deep Learning Learning Projects

---

## Future Improvements

- Deploy the model using Flask or FastAPI
- Develop a mobile application
- Integrate real-time camera-based prediction
- Support additional plant species
- Deploy on edge devices such as Raspberry Pi

---

## Author

**Harshit Sharma**

