# 🌸 Iris Classification using Artificial Neural Network (ANN)

## 📌 Overview
This project builds an Artificial Neural Network (ANN) using TensorFlow/Keras to classify iris flowers into three species based on four input features.

---

## 📊 Dataset
- Dataset: Iris Dataset  
- Samples: 150  
- Features:
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
- Target Classes:
  - Setosa  
  - Versicolor  
  - Virginica  

---

## 🧠 Model Architecture

Input Layer (4 features)
        ↓
Dense Layer (16 neurons, ReLU)
        ↓
Dense Layer (8 neurons, ReLU)
        ↓
Output Layer (3 neurons, Softmax)

- Total Parameters: 243

---

## ⚙️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 🔧 Data Preprocessing
- Feature Scaling using StandardScaler  
- Label Encoding using to_categorical  
- Train-Test Split  

---

## 🚀 Model Training

```python
model.compile(
    optimizer='adam',
    loss='categorical_crossentropy',
    metrics=['accuracy']
)

history = model.fit(
    X_train_scaled,
    y_train_cat,
    epochs=100,
    batch_size=8,
    validation_split=0.2
)
```

# visulization
<img width="840" height="390" alt="image" src="https://github.com/user-attachments/assets/3a9be7d6-e39a-422a-9764-32eb9f601f7a" />
<img width="831" height="352" alt="image" src="https://github.com/user-attachments/assets/d3fd18a4-48c0-4909-93b7-31b3d15f297e" />

