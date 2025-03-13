# 📝 Automated Nuclei Segmentation using U-Net – README

## 📌 Project Overview
This project focuses on developing an AI-powered automated nuclei detection system using semantic segmentation. The model is built using a U-Net architecture. The goal is to accurately segment nuclei in biomedical images by achieving 80%+ accuracy while ensuring the model does not overfit.

## 📂 Dataset
Dataset Source: 2018 Data Science Bowl – Kaggle
Link: https://www.kaggle.com/competitions/data-science-bowl-2018/overview 

## ⚙️ Project Workflow
This project follows a structured ML workflow:

### Problem Formulation

1. Define the problem: Semantic segmentation of cell nuclei.
2. Set success criteria: Achieve >80% accuracy while avoiding overfitting.

### Data Preparation

1. Load and preprocess images and masks.
2. Apply data augmentation techniques.
3. Split data into training and test sets.

### Model Development

1. Implement a U-Net architecture.
2. Use transfer learning.
3. Train the model with a target accuracy of 80%+.
4. Monitor for overfitting and apply regularization techniques.

### Model Evaluation

1. Assess performance using accuracy and loss.
2. Avoid overfitting using early stopping.

### Model Deployment & Prediction

1. Save the trained model.
2. Deploy the model to to predict nuclei on unseen test data.

### Results

Accuracy: 90% (>80% accuracy achieved)

## ⚙️ Model Architecture

![Model](img\model.png)

## 📊 Training Process & Model Performance

![Model](img\training_output.png)
Sample training prediction,training and validation accuracy and loss

![Model](img\accuracy_graph.png)
Accuracy graph during training process(epochs)

![Model](img\loss_graph.png)
Loss graph during training process(epochs)

![Model](img\prediction_output.png)
Sample test prediction

## Credit
https://www.kaggle.com/competitions/data-science-bowl-2018/overview 