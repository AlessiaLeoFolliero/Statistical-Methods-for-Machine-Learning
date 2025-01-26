# Statistical Methods for Machine Learning 📊  

This repository contains the project developed for the **Statistical Methods for Machine Learning** exam. The goal of the project was to design and evaluate at least three different architectures for a **binary image classification task**.  

## 🧁🐕 Project Overview  
- **Task**: Binary classification to distinguish between **muffins** and **chihuahuas**.  
- **Dataset**: Sourced from **Kaggle**.  
- **Approach**:  
  - Developed multiple **Convolutional Neural Networks (CNNs)** with varying architectures, layers, and parameters.  
  - Applied **hyperparameter tuning** using Keras and RandomSearch to optimize the models.  
  - Achieved a final classification accuracy of **93%**.  

---

## 🛠️ Libraries and Tools Used  
- **Data Manipulation**:  
  - `pandas`, `numpy`  
- **Deep Learning**:  
  - `tensorflow`, `keras`  
- **Visualization**:  
  - `matplotlib`, `PIL`  
- **Hyperparameter Tuning**:  
  - `keras-tuner`  

---

## 🧪 Key Features  
### 🛠️ Model Architectures  
Implemented three CNN architectures with combinations of:  
- **Convolutional Layers**:  
  - `Conv2D`, `MaxPooling2D`, `BatchNormalization`  
- **Dense Layers**:  
  - Fully connected layers with activation functions like `LeakyReLU` and `Dropout`.  
- **Data Augmentation**:  
  - Applied `RandomFlip` and `RandomRotation` to enhance generalization.  

### 🔍 Hyperparameter Tuning  
- Used **RandomSearch** and **Hyperband** with Keras Tuner to optimize:  
  - Number of filters in convolutional layers.  
  - Learning rate (using the Adam optimizer).  
  - Dropout rates and batch sizes.  

---

## 📈 Results  
- Final Accuracy: **93%**  
- The project demonstrates the effectiveness of carefully tuning hyperparameters and exploring different network architectures for binary image classification tasks.  

---

## 📬 Suggestions or Questions?  
Feel free to reach out with any suggestions or questions via GitHub issues or email.  


