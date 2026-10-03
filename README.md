# Walnut Cultivar Classification Using Deep Learning

A deep learning project for automated classification of **18 walnut cultivars from images**. The project evaluates multiple CNN and Transformer-based architectures and uses visualization and explainability techniques to understand model performance and predictions.

## 📌 Project Overview

Walnut cultivars can have visually similar characteristics, making automated identification a challenging computer vision task.

This project develops an image-classification pipeline to identify walnut cultivars using deep learning. It covers data preprocessing, augmentation, dataset splitting, model training, evaluation, visualization, and explainability.

## 🎯 Objectives

* Classify walnut images into **18 different cultivars**
* Compare multiple deep learning architectures
* Improve generalization using data augmentation
* Evaluate models using multiple performance metrics
* Analyze classification errors using confusion matrices
* Visualize learned feature representations using t-SNE
* Use Grad-CAM for model explainability
* Explore ensemble-based prediction

## 🗂️ Dataset

The dataset contains images belonging to **18 walnut cultivar classes**.

The images are processed and prepared for deep learning using preprocessing and augmentation techniques before being used for training and evaluation.

> Dataset files are not included in this repository unless permitted by the dataset license.

## 🔄 Project Pipeline

```text
Walnut Images
      ↓
Data Preprocessing
      ↓
Data Augmentation
      ↓
Stratified Train / Validation / Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Confusion Matrix & Performance Analysis
      ↓
t-SNE Feature Visualization
      ↓
Grad-CAM Explainability
      ↓
Ensemble Prediction
```

## 🤖 Models

The project benchmarks **six deep learning models**, including CNN and Transformer-based architectures.

The models are trained and evaluated using the same dataset pipeline to provide a comparative analysis of their classification performance.

## 🧪 Data Preprocessing

The preprocessing pipeline includes:

* Image resizing
* Normalization
* Data augmentation
* Stratified dataset splitting
* Train, validation, and test sets

Augmentation is used to improve model robustness and reduce overfitting.

## 📊 Evaluation

Model performance is analyzed using:

* Accuracy
* Classification performance
* Confusion matrix
* Per-class predictions
* Feature-space visualization

The confusion matrix helps identify which walnut cultivars are correctly classified and which classes are commonly confused.

## 🔍 Explainability

### Grad-CAM

Grad-CAM is used to visualize the regions of walnut images that contribute to model predictions. This provides insight into what visual features the model is focusing on during classification.

### t-SNE

t-SNE is used to visualize learned feature representations in a lower-dimensional space and examine how well different walnut cultivar classes are separated.

## 🔗 Ensemble Prediction

The project also explores ensemble prediction by combining outputs from multiple trained models to analyze whether combining model predictions can improve classification robustness.

## 📁 Project Structure

```text
Walnut-Cultivar-Classification/
│
├── notebook/
│   └── walnut_classification.ipynb
│
├── data/
│   └── dataset/
│
├── models/
│   └── trained_models/
│
├── results/
│   ├── confusion_matrices/
│   ├── gradcam/
│   └── tsne/
│
├── README.md
└── requirements.txt
```

## 🛠️ Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* OpenCV
* Jupyter Notebook

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/walnut-cultivar-classification.git
cd walnut-cultivar-classification
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Prepare the dataset

Place the walnut cultivar dataset in the appropriate dataset directory.

### 4. Run the notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells sequentially.

## 📈 Results

The notebook contains detailed experiments and visualizations for the evaluated models, including:

* Model comparison
* Confusion matrices
* Classification analysis
* t-SNE visualizations
* Grad-CAM visualizations
* Ensemble predictions

Refer to the notebook for the complete experimental results.

## 🔬 Future Improvements

Possible future improvements include:

* Larger and more diverse walnut datasets
* Additional pretrained architectures
* Hyperparameter optimization
* Deployment as a web or mobile application
* Real-time walnut cultivar identification
* Further ensemble and model-compression techniques


