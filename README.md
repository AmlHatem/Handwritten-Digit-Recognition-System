# 🔢 Handwritten Digit Recognition System

A Pattern Recognition and Machine Learning project for recognizing handwritten digits using:

- Wavelet Transform
- Principal Component Analysis (PCA)
- Support Vector Machine (SVM)

The project uses the famous MNIST handwritten digit dataset and applies multiple feature extraction and dimensionality reduction techniques to improve classification performance.

---

# 🚀 Project Overview

The main goal of this project is to recognize handwritten digits from images using Pattern Recognition techniques.

The system processes digit images through several stages:
1. Image preprocessing
2. Feature extraction using Wavelet Transform
3. Dimensionality reduction using PCA
4. Classification using SVM

The model predicts digits from:
- 0 → 9

---

# 🧠 Project Workflow

## 🔹 Step 1: Load Dataset

The project uses the famous MNIST dataset containing handwritten digit images.

### Dataset Features
- 70,000 handwritten digit images
- 28×28 grayscale images
- Labels from 0 to 9

For faster execution, a subset of the dataset was used.

---

# 🖼️ Image Visualization

The project displays:
- Original handwritten digit images
- Processed wavelet-transformed images
- PCA visualization results
- Prediction examples

This helps analyze how the model processes image data.

---

# 🌊 Wavelet Transform

## 🔹 Haar Wavelet Transform

Wavelet Transform was used for feature extraction.

### Why Wavelets?
Wavelets help capture:
- Edges
- Shapes
- Texture information
- Frequency details

### Technique Used
```python
pywt.dwt2()
```

The image is decomposed into:
- LL → Approximation coefficients
- LH → Horizontal details
- HL → Vertical details
- HH → Diagonal details

### Benefits
- Reduces noise
- Extracts important visual features
- Improves classification quality

---

# 📉 Principal Component Analysis (PCA)

## 🔹 Dimensionality Reduction

PCA was applied to reduce the feature space while preserving important information.

### Why PCA?
- Reduces computational complexity
- Removes redundant information
- Improves model efficiency
- Speeds up training

### Technique Used
```python
PCA(n_components=50)
```

### Features
- Compresses feature vectors
- Preserves important variance
- Helps visualization of data distribution

---

# 🤖 Support Vector Machine (SVM)

## 🔹 Classification Model

The project uses Support Vector Machine for digit classification.

### Technique Used
```python
SVC()
```

### Why SVM?
- High performance in classification tasks
- Effective with high-dimensional data
- Works well for image recognition problems

### Used For
- Predicting handwritten digits
- Multi-class classification
- Pattern recognition tasks

---

# 📊 Evaluation Methods

The project evaluates model performance using:

## 🔹 Accuracy Score
Measures overall prediction accuracy.

---

## 🔹 Classification Report
Provides:
- Precision
- Recall
- F1-Score

for each digit class.

---

## 🔹 Confusion Matrix
Visualizes:
- Correct predictions
- Misclassifications
- Model performance per class

---

# 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- PyWavelets
- Scikit-learn

---

# ⚙️ System Workflow

## 🔹 Input
Handwritten digit images from the MNIST dataset.

---

## 🔹 Processing
The system performs:
- Image reshaping
- Wavelet feature extraction
- PCA dimensionality reduction
- Feature transformation

---

## 🔹 Classification
SVM predicts the handwritten digit class.

---

## 🔹 Output
The system outputs:
- Predicted digit labels
- Accuracy metrics
- Visualization graphs
- Confusion matrix

---

# 📈 Features

✅ Wavelet-based feature extraction  
✅ PCA dimensionality reduction  
✅ SVM classification  
✅ Visualization of transformed images  
✅ Confusion matrix analysis  
✅ Handwritten digit recognition  

---

# ▶️ How to Run

```bash
# Clone repository
git clone https://github.com/your-username/your-repository-name.git

# Open project folder
cd your-repository-name

# Install requirements
pip install -r requirements.txt

# Run project
python main.py
```

---

# 📌 Project Goals

- Apply Pattern Recognition concepts
- Understand image feature extraction
- Learn dimensionality reduction techniques
- Build an intelligent handwritten digit classifier
- Improve image classification performance

---

# 📈 Future Improvements

- Real-time digit recognition
- CNN deep learning implementation
- Higher dataset optimization
- Better feature engineering techniques
- GUI integration for live digit prediction

---

# 👩‍💻 Author

Developed as a Pattern Recognition and Machine Learning project for educational and research purposes.
