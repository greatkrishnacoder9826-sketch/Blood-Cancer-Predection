# 🩸 Blood Cell Cancer Detection using Machine Learning

## 📌 Project Overview

This project is a Machine Learning based image classification system that detects different types of blood cell cancer from microscopic blood cell images.

The model is trained using image processing techniques and a Support Vector Machine (SVM) classifier to classify blood cell images into multiple categories.

---

# 🚀 Features

* Image classification using Machine Learning
* Blood cancer cell detection
* Multi-class prediction system
* Image preprocessing and resizing
* Model training using SVM
* Hyperparameter tuning using GridSearchCV
* Accuracy evaluation
* Predicts different blood cell categories

---

# 🧠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* scikit-image
* Jupyter Notebook

---

# 📂 Dataset Categories

The dataset contains the following classes:

1. Benign
2. [Malignant] Pro-B
3. [Malignant] Pre-B
4. [Malignant] early Pre-B

---

# ⚙️ Machine Learning Workflow

## 1️⃣ Data Loading

Images are loaded from dataset folders using Python.

## 2️⃣ Image Preprocessing

* Image resizing
* Flattening image arrays
* Feature extraction

## 3️⃣ Dataset Creation

The processed image data is converted into a Pandas DataFrame.

## 4️⃣ Train-Test Split

Dataset is divided into:

* Training Data
* Testing Data

## 5️⃣ Model Training

The model uses:

```python
svm.SVC(probability=True)
```

## 6️⃣ Hyperparameter Tuning

GridSearchCV is used for finding the best parameters.

```python
param_grid = {
    'C': [0.1, 1, 10, 100],
    'gamma': [0.0001, 0.001, 0.1, 1],
    'kernel': ['rbf', 'poly']
}
```

## 7️⃣ Prediction & Evaluation

The model predicts cancer categories and calculates accuracy.

---

# 📊 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from skimage.transform import resize
from skimage.io import imread
from sklearn import svm
from sklearn.model_selection import train_test_split, GridSearchCV
from sklearn.metrics import accuracy_score
```

---

# 📁 Project Structure

```bash
├── Blood_Cancer_Detection.ipynb
├── dataset/
│   ├── Benign/
│   ├── [Malignant] Pro-B/
│   ├── [Malignant] Pre-B/
│   └── [Malignant] early Pre-B/
└── README.md
```

---

# ▶️ How to Run

## Step 1: Clone Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

## Step 2: Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn scikit-image
```

## Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

## Step 4: Run the Notebook

Open the notebook and run all cells.

---

# 📈 Future Improvements

* Deep Learning implementation using CNN
* Better accuracy optimization
* Real-time prediction system
* Web application deployment
* Model saving and loading

---

# 🎯 Learning Outcomes

This project helps in understanding:

* Image classification
* Medical image processing
* Support Vector Machine (SVM)
* Hyperparameter tuning
* Data preprocessing
* Machine Learning workflow

---

# 🤝 Contribution

Contributions are welcome.
Feel free to fork this repository and improve the project.

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 👨‍💻 Author

Krishna Great
