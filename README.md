# CrayonsClassifier_MLP-Classification_CNN_Project

##  Overview  
This project explores two deep learning approaches to classify crayon images into multiple categories.  
I started with a **Multi-Layer Perceptron (MLP)** as a baseline model, then improved performance using a **Convolutional Neural Network (CNN)**.  
The goal was to demonstrate the impact of model architecture on image classification accuracy.  

Beyond technical performance, this project highlights how image classification can be applied to **children’s drawings**. By categorizing crayon sketches, parents and guardians can gain insights into the recurring themes, objects, or colors their kids use. Such analysis can provide clues into children’s **emotions, preferences, and psychological states**, offering a supportive tool to better understand their inner world.  

---

I started with a **Multi-Layer Perceptron (MLP)** as a baseline model, then improved performance using a **Convolutional Neural Network (CNN)**.  
The goal was to demonstrate the impact of model architecture on image classification accuracy.  

---

##  Methodology

### 1. Data Preparation
- **Dataset**: 4242 labeled crayon images across **5 emotion classes**.  
- Preprocessing: resizing, normalization, and augmentation to reduce overfitting.  
- Train/test split for evaluation.  

### 2. Modeling
#### 🔹 Baseline: MLP Classifier
- Flattened images into 1D arrays.  
- Implemented an **MLP** with hidden layers and ReLU activations.  
- Achieved **.15% test accuracy**.  

#### 🔹 Improved: CNN Classifier
- Designed a **Convolutional Neural Network** with convolution + pooling layers.  
- Leveraged image spatial structure for feature extraction.  
- Achieved **35% test accuracy**, outperforming MLP.  

### 3. Evaluation
- Compared **accuracy curves** and **loss plots** between models.  
- CNN showed better generalization and reduced overfitting.  

---

##  Results
- **MLP**: Good baseline, but struggled with spatial patterns.  
- **CNN**: Captured image features much more effectively → **34% accuracy gain**.
- Can be vastly improved using a larger real-life data set.

Example accuracy comparison:  
- MLP Accuracy: **0.15%**  
- CNN Accuracy: **35%**  

---


