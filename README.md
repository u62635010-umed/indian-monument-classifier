# 🏛 Indian Monument Classifier

A CNN-based multi-class image classification model that identifies 24 Indian monuments using Deep Learning.  
The model is deployed with a Streamlit web interface for real-time predictions.

---

## 🚀 Features

- Multi-class Image Classification (24 monuments)
- Custom CNN architecture built using TensorFlow & Keras
- Data Augmentation for better generalization
- L2 Regularization + Dropout for overfitting control
- Streamlit-based interactive UI
- Real-time prediction with confidence score

---

## 🧠 Model Architecture

- 4 Convolutional Blocks (Conv2D + BatchNorm + MaxPooling)
- L2 Regularization
- Fully Connected Layers with Dropout
- Softmax Output Layer (24 classes)

Input Shape: `(150, 150, 3)`  
Optimizer: `Adam (learning_rate=0.0001)`  
Loss Function: `Categorical Crossentropy`  
Validation Accuracy: ~82%

---

## 📂 Project Structure

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/indian-monument-classifier.git
cd indian-monument-classifier
pip install -r requirements.txt
streamlit run app.py
