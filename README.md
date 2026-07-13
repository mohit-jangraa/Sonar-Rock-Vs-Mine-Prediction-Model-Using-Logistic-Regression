# 🪨 Sonar Rock vs Mine Prediction using Logistic Regression

A Machine Learning project that predicts whether an object detected by SONAR is a **Rock** or a **Mine** using the **Logistic Regression** algorithm.

---

## 📌 Project Overview

Sonar (Sound Navigation and Ranging) systems send sound waves underwater and record the reflected signals. Each object produces a unique sonar signature.

This project trains a Logistic Regression model on SONAR signal data to classify underwater objects into:

- 🪨 Rock (R)
- 💣 Mine (M)

---

## 📂 Dataset

The dataset contains sonar signals reflected from different underwater objects.

### Features

- **60 numerical features**
- Each feature represents the energy of a sonar signal within a specific frequency band.

### Target Variable

| Label | Meaning |
|-------|---------|
| R | Rock |
| M | Mine |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📊 Machine Learning Workflow

```
Import Libraries
        │
        ▼
Load Dataset
        │
        ▼
Data Exploration
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
(Logistic Regression)
        │
        ▼
Model Evaluation
        │
        ▼
Prediction on New Data
```

---

## 📁 Project Structure

```
Sonar-Rock-vs-Mine-Prediction/
│
├── data/
│   └── Copy_of_sonar_data.csv
│
├── notebook/
│   └── Sonar_Rock_vs_Mine_Prediction.ipynb
│
├── models/
│   └── logistic_regression_model.pkl
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Sonar-Rock-vs-Mine-Prediction.git
```

Move into the project folder

```bash
cd Sonar-Rock-vs-Mine-Prediction
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 🚀 Model Training

The dataset is divided into training and testing sets using:

- **Training Data:** 80%
- **Testing Data:** 20%

The model is trained using **Logistic Regression** from Scikit-Learn.

---

## 📈 Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Confusion Matrix 
- Classification Report 

Example:

```
Training Accuracy : XX.XX%

Testing Accuracy  : XX.XX%
```

---

## 🔮 Prediction Example

```python
input_data = (
    ...
)

prediction = model.predict(input_data)

if prediction[0] == 'R':
    print("Prediction: Rock")
else:
    print("Prediction: Mine")
```

Example Output

```
Prediction: Rock
```

---

## 📚 Concepts Covered

- Binary Classification
- Logistic Regression
- Data Preprocessing
- Train-Test Split
- Model Training
- Model Evaluation
- Prediction using Machine Learning

---

## 🎯 Future Improvements

- Build a Streamlit web application
- Deploy the model online
- Compare Logistic Regression with:
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)

---

## 👨‍💻 Author

**Mohit Jangra**

B.Tech CSE Student | Aspiring AI/ML Engineer

---

## ⭐ If you found this project helpful, consider giving it a star!
