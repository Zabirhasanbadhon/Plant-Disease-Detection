# 🌿 Plant Leaf Disease Detection Using CNN

A deep learning project that detects plant leaf diseases using Convolutional Neural Networks (CNN) with Python and TensorFlow/Keras.

## 🚀 Features

- CNN-based plant disease classification.
- Detects three categories: Healthy, Powdery, and Rust.
- Loads image datasets from local folders.
- Image preprocessing and augmentation.
- Training and validation accuracy visualization.
- Saves the trained model as `plantdiseasemodel.h5`.
- Predicts disease categories from leaf images.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Pillow
- Jupyter Notebook

## 📂 Project Structure

```text
Plant-Leaf-Disease-Detection-CNN/
│
├── Model_Training.ipynb
├── app.py
├── plantdiseasemodel.h5
├── README.md
├── Dataset/
│   ├── Train/
│   ├── Test/
│   └── Validation/
└── requirements.txt
```

## 📊 Model Information

- Model: Convolutional Neural Network (CNN)
- Image Size: 225 × 225
- Classes: 3
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Epochs: 5

## ⚙️ Installation

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib seaborn pillow jupyter
```

Run Jupyter Notebook:

```bash
python -m notebook
```

Open `Model_Training.ipynb` and run the cells to train the model.

## 💾 Trained Model

The trained model is saved as:

```text
plantdiseasemodel.h5
```

Load the model using:

```python
from tensorflow.keras.models import load_model

model = load_model("plantdiseasemodel.h5")
```

## 👨‍💻 Author

**Zabir Hasan**

🌐 Website: https://www.zabirhasan.com

---
