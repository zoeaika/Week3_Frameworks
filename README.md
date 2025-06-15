# Week3_Frameworks
✅ Task 1: Classical ML with Scikit-learn (Iris Dataset)
Status: ✅ Completed Successfully
Highlights:

Loaded and explored the Iris dataset.
Checked for missing values (none found).
Standardized features using StandardScaler.
Trained a DecisionTreeClassifier.
Achieved perfect evaluation metrics:
Accuracy: 1.0
Precision: 1.0
Recall: 1.0
Task 2: Deep Learning with TensorFlow/PyTorch
Project: MNIST Handwritten Digit Classifier

📌 Overview
This project builds a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset using TensorFlow. The goal is to achieve over 95% accuracy and visualize predictions on test samples.

✅ Features
CNN model trained on MNIST

Achieves >95% test accuracy

Visualizes predictions on 5 random test images

🛠 Requirements
Python 3

TensorFlow

NumPy

Matplotlib
Task 3: NLP with spaCy
Project: Entity Extraction and Sentiment Analysis on Amazon Reviews

📝 Overview
This script uses spaCy to extract product and brand names from Amazon reviews, and TextBlob for basic sentiment analysis. It also touches on ethical concerns and debugging in NLP and ML systems.

🔍 Features
Named Entity Recognition (NER) for brands and products

Rule-based sentiment (positive/negative/neutral)

Sample output shows both extracted data and sentiment per review

⚖️ Ethics & Debugging
Discusses potential biases in sentiment models (e.g., language bias, brand stereotypes)

Explains how tools like spaCy rule-based systems or TensorFlow Fairness Indicators can help reduce bias

Includes a sample fix for a common TensorFlow bug (wrong loss function or activation)

🛠 Requirements
spaCy

TextBlob

en_core_web_sm model (download with python -m spacy download en_core_web_sm)
