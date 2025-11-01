# ANN-model-building_Iris-species-classification-
A beginner-friendly deep learning project that classifies Iris flower species using a simple Artificial Neural Network (ANN) built with TensorFlow and Keras. Includes data preprocessing, model training, accuracy visualization, and insights.

# 🌸 Iris Species Classification using Artificial Neural Network (ANN)

This project demonstrates how to build and train a **neural network from scratch using TensorFlow/Keras** to classify **Iris flower species** based on their physical measurements.  
It’s one of the most iconic datasets in machine learning — and this notebook turns it into a clean, beginner-friendly example of deep learning applied to a small, interpretable problem.

---

## 🎯 Project Overview
The goal of this project is to classify flowers into one of three Iris species:
- **Iris Setosa**
- **Iris Versicolor**
- **Iris Virginica**

using four features:
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

The dataset contains **150 labeled samples**, making it perfect for visual learning and experimentation with ANN architectures.

---

## 🧠 Why This Project
I built this project to explore how a **neural network learns from small datasets**, how **activation functions** affect training, and how model performance changes over epochs.  
Even though the Iris dataset is simple, the goal here is to **understand ANN fundamentals**, not just get high accuracy.

---

## ⚙️ Model Architecture

| Layer | Type | Units | Activation |
|-------|------|--------|-------------|
| Input | Dense | 4 | ReLU |
| Hidden | Dense | 12 | ReLU |
| Output | Dense | 3 | Softmax |

**Loss Function:** Categorical Crossentropy  
**Optimizer:** Adam  
**Metrics:** Accuracy

---

## 🧩 Key Steps
1. **Data Preprocessing** – Load and normalize the Iris dataset using `scikit-learn`.  
2. **Model Building** – Define a Sequential ANN with multiple dense layers.  
3. **Training** – Train the model for 100 epochs with an 80–20 train–test split.  
4. **Evaluation** – Compare training and testing accuracy and visualize results.  
5. **Visualization** – Plot accuracy over epochs to analyze model performance.

---

## 📈 Results
The model achieved:
- ✅ **~92% Training Accuracy**
- ✅ **~85–88% Test Accuracy**

The plot below shows a consistent improvement in both training and validation accuracy, proving stable learning and minimal overfitting.



---

## 🛠️ Technologies Used
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**

---

## 🌱 What I Learned
- Designing and tuning a small-scale ANN  
- Importance of activation functions (ReLU vs Sigmoid)  
- Avoiding overfitting on small datasets  
- Visualizing model performance effectively  

---

## 🧩 How to Run
```bash
pip install tensorflow numpy pandas matplotlib scikit-learn
jupyter notebook
