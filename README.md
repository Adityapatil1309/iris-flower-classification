# Iris Flower Classification using Machine Learning

## 📌 Project Overview
This project builds and compares multiple machine learning models to classify Iris flower species. The goal is to analyze performance of different algorithms and select the best model.

---

## 📊 Dataset Information
- Dataset: Iris Dataset (Kaggle)
- Total Samples: 150
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Target: Species (Setosa, Versicolor, Virginica)

---

## ⚙️ Steps Performed

### 1. Data Preprocessing
- Loaded dataset using Pandas
- Checked for missing values (none found)
- Encoded categorical target variable using LabelEncoder

### 2. Feature Selection
- Input Features: Sepal Length, Sepal Width, Petal Length, Petal Width
- Target Variable: Species

### 3. Train-Test Split
- Train Size: 80%
- Test Size: 20%
- Random State: 42

---

## 🤖 Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy |
|------|----------|
| Logistic Regression | 1.00 |
| KNN | 1.00 |
| Random Forest | 1.00 |

---

## 🏆 Best Model
Random Forest Classifier performed best due to its robustness and ability to handle real-world complex patterns.

---

## 📸 Visualizations
- Accuracy comparison table (screenshot included)
- Confusion matrix (screenshot included)

Files:
- accuracy_table.png
- confusion_matrix.png

---

## 📌 Conclusion
This project demonstrates a complete machine learning workflow including preprocessing, training, evaluation, and model comparison. All models achieved high accuracy due to the simplicity of the dataset.

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## 📁 Repository Structure
