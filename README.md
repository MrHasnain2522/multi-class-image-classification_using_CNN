#Project title:
  Multi_class image classification using CNN

# intro:
 This project focuses on building a Convolutional Neural Network (CNN) model to classify images of various sports balls such as basketballs,
 footballs, tennis balls, volleyballs, and more.
 The model learns to identify visual patterns and textures unique to each type of ball and predicts the correct category when shown a new image.
 The task falls under multi-class image classification, and CNNs are particularly effective here due to their ability to automatically extract,
 spatial features from image data.

# Dataset Overview:
 - 🏀 Basketball  
 - ⚽ Football  
 - 🎾 Tennis Ball  
 - 🏐 Volleyball  
 - 🏈 American Footbal

# CNN Architecture:
 - Input Layer (e.g., 128x128x3)
 - Conv2D → ReLU → MaxPooling
 - Conv2D → ReLU → MaxPooling
 - Flatten
 - Dense → ReLU
 - Dropout (for regularization)
 - Dense → Softmax (for multi-class prediction)

# 🔧 Tools & Libraries:

- Python  
- TensorFlow / Keras  
- OpenCV (for image handling)  
- NumPy, pandas  
- Matplotlib, seaborn  
- Jupyter Notebook / Google Colab

## 🚀 Project Workflow:
1. **Data Collection / Loading**  
2. **Preprocessing** (load_data using keras,resizing, normalization )  
3. **Model Building** (CNN architecture using Keras Sequential API)  
4. **Training & Validation**  
5. **Model Evaluation** (accuracy, loss, confusion matrix)  
6. **Visualization of Results**

## ✅ Results

- Training Accuracy: 0.87 
- Validation Accuracy: 0.52 
- Test Accuracy: ~XX%






