# 🌿 Plant Species Classification using Transfer Learning

A deep learning-based image classification system that identifies house plant species from images using **Transfer Learning** with TensorFlow and Keras. The project demonstrates an end-to-end computer vision workflow, including data preprocessing, model training, fine-tuning, evaluation, and prediction.

---

## 📖 Overview

Plant species identification is an important application of computer vision in agriculture, horticulture, and botanical research. This project leverages a pretrained Convolutional Neural Network (CNN) to accurately classify different house plant species from images.

The notebook covers the complete deep learning pipeline—from dataset preparation and augmentation to transfer learning, model fine-tuning, performance evaluation, and prediction on unseen images.

---

## ✨ Features

- Image dataset preprocessing and cleaning
- Automatic training, validation, and test dataset creation
- Data augmentation for improved model generalization
- Transfer learning using a pretrained CNN
- Fine-tuning for higher classification accuracy
- Performance evaluation using accuracy and loss metrics
- Prediction on new plant images
- Training history visualization
- End-to-end implementation in Jupyter Notebook

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```text
Plant-Species-Classification-Transfer-Learning/
│
├── model-final.ipynb        # Model training and evaluation notebook
├── requirements.txt         # Project dependencies
├── README.md                # Project documentation
└── .gitignore
```

---

## 📊 Dataset

The model is trained on an image dataset containing multiple house plant species.

### Dataset Preparation

- Remove corrupted or invalid images
- Organize images into class-specific folders
- Split dataset into:
  - Training Set
  - Validation Set
  - Test Set
- Apply data augmentation techniques to improve robustness

> **Note:** The dataset is not included in this repository due to its size.

---

## 🧠 Model Architecture

The project uses **Transfer Learning** with a pretrained Convolutional Neural Network.

```text
Input Image
      │
      ▼
Pretrained CNN Backbone
      │
      ▼
Global Average Pooling
      │
      ▼
Dropout Layer
      │
      ▼
Dense Softmax Classifier
      │
      ▼
Predicted Plant Species
```

After initial training, selected layers of the pretrained model are fine-tuned to further improve classification performance.

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/harshit-s11/Plant-Species-Classification-Transfer-Learning.git
```

### Navigate to the project directory

```bash
cd Plant-Species-Classification-Transfer-Learning
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
model-final.ipynb
```

---

## 🚀 Usage

1. Download the plant species dataset.
2. Update the dataset path in the notebook.
3. Run all notebook cells sequentially.
4. Train the transfer learning model.
5. Fine-tune the pretrained layers.
6. Evaluate model performance.
7. Predict plant species for new images.

---

## 📈 Results

The notebook provides detailed evaluation including:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Model Evaluation Metrics
- Prediction Results
- Training Performance Graphs

---

## 🌱 Applications

- Smart Gardening
- Plant Species Identification
- Agricultural Technology
- Botanical Research
- Educational Deep Learning Projects
- Computer Vision Applications

---

## 🔮 Future Improvements

- Deploy the model using Flask or FastAPI
- Build a Streamlit web application
- Develop a mobile application
- Support additional plant species
- Real-time camera-based prediction
- Edge deployment on Raspberry Pi
- Export the model using TensorFlow Lite

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

**Harshit Sharma**

If you found this project useful, consider giving it a ⭐ on GitHub.
