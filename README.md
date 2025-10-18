# 🥦 Vegetable Image Classification with Machine Learning

A machine learning project that identifies the **type of vegetable** in an image using a **Convolutional Neural Network (CNN)** — delivering accurate and reliable results.

---

## 📘 Project Overview
This project implements a CNN-based image classifier capable of recognizing **15 types of vegetables**:

| # | Vegetable Name |
|---|----------------|
| 1 | Bean |
| 2 | Bitter Gourd |
| 3 | Bottle Gourd |
| 4 | Brinjal |
| 5 | Broccoli |
| 6 | Cabbage |
| 7 | Capsicum |
| 8 | Carrot |
| 9 | Cauliflower |
|10 | Cucumber |
|11 | Papaya |
|12 | Potato |
|13 | Pumpkin |
|14 | Radish |
|15 | Tomato |

---

## 🗂️ Dataset Structure
The dataset follows this directory organization:

```text
Vegetable_Images/
├── train/          # Training images (1000 per class)
├── test/           # Test images (200 per class)
└── validation/     # Validation images (200 per class)
```
---

## 🧩 Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x  
- TensorFlow  
- TensorFlow Hub  
- NumPy  
- Pandas  
- Matplotlib  
- scikit-learn  
- Pillow (PIL)

---

## ⚙️ Installation

Install all dependencies with:
```bash
pip install tensorflow tensorflow-hub numpy pandas matplotlib scikit-learn pillow
```
Install the dataset on this link provided.
https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset

NOTE: The dataset must be in the same directory from the project folder

## ⚙️ Project Setup

1. **Clone the repository** or **download the notebook file**
   ```bash
   git clone https://github.com/FhatrkFheng/Vegetable-Image-Classification-with-machine-learning.git
   ```

2. Run the whole program to create the model

## 🌟 Key Features

- **Data Validation:** Checks image formats and balances dataset  
- **Data Augmentation:** Uses `ImageDataGenerator` for robust training  
- **Transfer Learning:** Optionally leverages pre-trained models via **TensorFlow Hub**  
- **Model Checkpoints:** Automatically saves the best-performing models during training  
- **Comprehensive Evaluation:** Generates confusion matrix and accuracy metrics  

---

## 📈 Model Performance

The model classifies images across **15 vegetable categories**, providing the following metrics:

- Training accuracy  
- Validation accuracy  
- Test accuracy  
- Per-class precision and recall  

---

## 🗂️ File Structure
``` bash
Vegetable Classification.ipynb # Main notebook file
Vegetable_Images/ # Dataset directory
archive (2).zip # Compressed dataset file
```


---

## 💡 Usage Tips

- **GPU Recommendation:** Use a GPU-enabled environment for faster training  
- **Memory Management:** The dataset contains ~21,000 images; ensure adequate RAM  
- **Customization:** Adjust hyperparameters in the model architecture for experimentation  
- **Extension:** The model can be expanded to classify additional vegetable types  

---

## 🛠️ Troubleshooting

- If you encounter **memory issues**, reduce the batch size  
- For **dataset path errors**, verify the extraction path matches your code  
- Ensure all images are in **JPG format** as expected by the preprocessing pipeline  

---

## 🥕 Results

The model delivers a **robust vegetable classification system** suitable for:

- 🌾 Agricultural analysis  
- 🥗 Food recognition systems  
- 🎓 Educational or research applications  

---

