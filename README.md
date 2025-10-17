# 🧠 TensorFlow Study Material & Practice Guide  

## 📘 Overview  
Welcome to my **TensorFlow learning repository**!  
This repo contains all my **study notes, code exercises, and practice projects** covering TensorFlow fundamentals, neural networks, and classification models.  

TensorFlow is Google’s open-source **Machine Learning and Deep Learning framework**, designed to build, train, and deploy neural networks efficiently on CPUs, GPUs, and TPUs.  

---

## 🎯 Learning Objectives  
Through this repository, I aim to:  
- ✅ Understand TensorFlow tensors and basic operations  
- ✅ Build and train neural networks using `tf.keras`  
- ✅ Perform binary and multiclass classification  
- ✅ Use activation functions, optimizers, and loss functions effectively  
- ✅ Visualize learning progress and model decision boundaries  
- ✅ Prepare for CNNs, RNNs, and advanced Deep Learning models  

---

## 📂 Folder Structure  
│
├── 01_TensorFlow_Fundamentals.ipynb # Tensors, GPU usage, operations
├── 02_Neural_Network_Basics.ipynb # Dense layers, activations, Sequential API
├── 03_Binary_Classification.ipynb # Sigmoid, binary_crossentropy, accuracy
├── 04_Multiclass_Classification.ipynb # Softmax, SparseCategoricalCrossentropy
├── 05_Model_Visualization.ipynb # Decision boundaries, plots
│
├── /datasets/ # Sample datasets for training/testing
│ ├── binary_data.csv
│ ├── multiclass_data.csv
│
├── /images/ # Training result screenshots and graphs
│
└── README.md # Study guide and reference

---

## 🧩 Topics Covered  

### 🔹 **1. TensorFlow Fundamentals**
- Tensor creation and manipulation  
- Tensor operations and reshaping  
- GPU/TPU device management  
- Automatic differentiation with `tf.GradientTape()`  

### 🔹 **2. Neural Networks**
- Building Sequential models with `tf.keras`  
- Using `Dense` layers with different activations  
- Common activations: `relu`, `sigmoid`, `softmax`  
- Compiling models with optimizers (`Adam`, `SGD`) and losses  

### 🔹 **3. Binary Classification**
- Predicting two categories (0 or 1)  
- Using `sigmoid` activation and `binary_crossentropy`  
- Metrics: Accuracy, Precision, Recall  
- Visualizing decision boundaries  

### 🔹 **4. Multiclass Classification**
- Handling more than two output classes  
- Using `softmax` activation and `SparseCategoricalCrossentropy`  
- Evaluating model with accuracy and confusion matrix  
- Visualizing training and validation performance  

---

## 🧠 Practice Exercises  

| Level | Task | Focus |
|--------|------|-------|
| 🟢 Basic | Create tensors and perform basic math ops | TensorFlow basics |
| 🟡 Intermediate | Build a simple neural network | Dense layers, activations |
| 🟠 Advanced | Train binary & multiclass models | Classification, metrics |
| 🔵 Visualization | Plot accuracy/loss and decision boundaries | Model evaluation |

---

## ⚙️ Setup Instructions  

```bash
# Clone this repository
git clone https://github.com/<your-username>/TensorFlow_Study.git
cd TensorFlow_Study

# Create a virtual environment
python -m venv tf-env
source tf-env/bin/activate  # On Windows: tf-env\Scripts\activate

# Install dependencies
pip install tensorflow numpy matplotlib scikit-learn
