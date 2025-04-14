# 🧠 Handwritten Digit Recognition using MNIST Dataset

This project implements a handwritten digit recognition system using the **MNIST dataset**, comparing the performance of three deep learning models: **ANN**, **CNN**, and **RNN**.

## 📚 Dataset

- **Dataset**: MNIST (Modified National Institute of Standards and Technology)
- **Total Images**: 70,000 grayscale images (60,000 training + 10,000 testing)
- **Image Size**: 28x28 pixels
- **Classes**: 10 (Digits 0–9)

## 🧪 Models Implemented

### 🔹 1. Artificial Neural Network (ANN)
- Simple fully connected architecture
- Input layer → Hidden layers → Output layer
- Flattened 28x28 images into 784 inputs

### 🔹 2. Convolutional Neural Network (CNN)
- Multiple convolutional and pooling layers
- Captures spatial features efficiently
- Best performing model among the three

### 🔹 3. Recurrent Neural Network (RNN)
- Used flattened image as time sequences
- Explored for experimentation on image data
- Comparatively lower accuracy than CNN

---

## 📊 Accuracy vs Epochs

### 🔸 ANN Accuracy

![image](https://github.com/user-attachments/assets/68022b44-84f0-4795-9cb1-6dd2a259c89c)

### 🔸 CNN Accuracy

![image](https://github.com/user-attachments/assets/32b64c3f-2397-483f-a2b4-7695fbeb6795)


### 🔸 RNN Accuracy

![image](https://github.com/user-attachments/assets/23101364-5413-4676-9e72-1e8d7acb09e9)


---

## 📉 Loss vs Epochs

### 🔸 ANN Loss

![image](https://github.com/user-attachments/assets/9e6da3f9-6e5d-4433-ac90-b6fb1325a81b)


### 🔸 CNN Loss

![image](https://github.com/user-attachments/assets/05cd2a04-dc29-4031-afce-787ce0c3f1ae)




### 🔸 RNN Loss

![image](https://github.com/user-attachments/assets/c8c2d5d8-a4ae-4d9a-a50c-a354ba132e50)


---

## 🖼️ Epoch Training Screenshots

### 🔸 ANN Epochs Output

![image](https://github.com/user-attachments/assets/7d4ec571-ac42-4db5-9f2f-8f736b19af0f)


### 🔸 CNN Epochs Output

![image](https://github.com/user-attachments/assets/b18e543a-f586-4e3d-8c0e-664ec8a01176)


### 🔸 RNN Epochs Output

![image](https://github.com/user-attachments/assets/7b273f99-55f7-4195-8a12-5cb0275449e9)


---

## ✅ Summary

| Model | Accuracy | Training Speed | Best Use Case |
|-------|----------|----------------|----------------|
| ANN   | Moderate | Fast           | Simple tasks and baselines |
| CNN   | High     | Efficient      | Image recognition tasks |
| RNN   | Lower    | Slower         | Sequential or time series data |

---

## 📌 Note

This project demonstrates comparative learning approaches for image classification using one of the most iconic datasets in the deep learning world.

