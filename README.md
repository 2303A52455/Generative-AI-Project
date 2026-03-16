# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the presence of **heart disease** using various **machine learning and deep learning algorithms**. The dataset is analyzed, preprocessed, and used to train multiple models to compare their performance in predicting heart disease.

The project demonstrates how machine learning techniques can assist in **early detection of heart disease**, which can help healthcare professionals make better decisions.

---

## 📊 Dataset

The project uses a **Heart Disease dataset (`heart.csv`)** containing patient health parameters.

### Features in the Dataset

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG Results
* Maximum Heart Rate
* Exercise Induced Angina
* ST Depression
* ST Slope

### Target

* **HeartDisease**

  * `0` → No Heart Disease
  * `1` → Heart Disease Present

---

## 🛠 Technologies Used

* **Python**
* **TensorFlow / Keras**
* **Scikit-learn**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **XGBoost**

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading

The dataset is loaded using **Pandas** and inspected for structure and missing values.

### 2️⃣ Data Preprocessing

* Encoding categorical variables using **LabelEncoder**
* Feature scaling using **StandardScaler**
* Splitting dataset into **training and testing sets**

### 3️⃣ Exploratory Data Analysis

Visualizations were created to understand data distribution, such as:

* Age distribution histogram
* Feature analysis using **Seaborn and Matplotlib**

### 4️⃣ Model Training

Multiple machine learning models were trained and evaluated:

* Artificial Neural Network (ANN)
* Support Vector Machine (SVM)
* Logistic Regression
* XGBoost
* Random Forest

### 5️⃣ Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve

---

## 🧠 Deep Learning Model (ANN)

A **Neural Network** was built using TensorFlow/Keras with:

* Input Layer
* Dense Hidden Layers
* Dropout for regularization
* Adam optimizer
* Binary Crossentropy loss function

The model was trained for **350 epochs**.

---

## 📈 Performance Metrics

Each model's performance was compared based on accuracy and classification reports to determine the best-performing algorithm.

Metrics used:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Curve

---

## 📊 Model Comparison

The following models were compared:

| Model               | Description                          |
| ------------------- | ------------------------------------ |
| Neural Network      | Deep learning model using TensorFlow |
| SVM                 | Support Vector Machine classifier    |
| Logistic Regression | Linear classification model          |
| XGBoost             | Gradient boosting algorithm          |
| Random Forest       | Ensemble learning method             |

---

## 💾 Model Saving

The trained neural network model can be saved and loaded later using:

```python
model.save("HeartDiseasePrediction.h5")
```

To load the model:

```python
from tensorflow.keras.models import load_model
model = load_model("HeartDiseasePrediction.h5")
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/HeartDiseasePrediction.git
```

### 2️⃣ Install Dependencies

```bash
pip install pandas numpy scikit-learn tensorflow seaborn matplotlib xgboost
```

### 3️⃣ Run the Notebook

Open the Jupyter notebook:

```bash
jupyter notebook HeartDiseasePrediction.ipynb
```

---

## 📌 Future Improvements

* Hyperparameter tuning for better performance
* Deploying the model as a **web application**
* Integrating real-time healthcare data
* Adding feature importance visualization

---

## 👩‍💻 Author

**Tejasri Aidalapuram**
