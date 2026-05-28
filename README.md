# Artificial Intelligence Lab Assignment

This repository contains solutions and implementations for an Artificial Intelligence lab assignment using Python, Machine Learning, and Neural Networks in Google Colab.

---

# Project Contents

## Part One — Multi-Agent Systems

### Task 1 — Basic Agent

Implemented a simple agent system using Python classes.

Features:

* Agent initialization with name and location
* Environment perception
* Agent actions simulation

Concepts used:

* Object-Oriented Programming (OOP)
* Encapsulation
* Class methods

---

### Task 2 — Communicating Agent

Extended the basic agent to support communication between agents.

Features:

* Sending messages between agents
* Inbox system
* Message display functionality

Concepts used:

* Inheritance
* Message passing
* Multi-agent interaction

---

### Task 3 — Multi-Agent Simulation (Rock Paper Scissors)

Developed an interactive Rock-Paper-Scissors game between a player and a computer agent.

Features:

* Menu-driven interface
* Input validation
* Randomized computer choices
* Multiple rounds support
* Winner determination logic

Concepts used:

* Game simulation
* User interaction
* Randomization
* Decision making

---

# Part Two — Artificial Neural Networks

## Task 1 — Load and Explore the Data

Dataset used:

* Digits Dataset from Scikit-learn

Operations performed:

* Loading the dataset
* Converting data into a Pandas DataFrame
* Exploring dataset dimensions and structure

Dataset Information:

* Samples: 1797
* Features: 64
* Classes: 10 digits (0–9)

---

## Task 2 — Split the Data

Used `train_test_split` from Scikit-learn to divide the dataset into:

* Training set
* Testing set

Configuration:

* Test size: 20%
* Random state: 0

---

## Task 3 — Build the Neural Network

Built a simple Artificial Neural Network using TensorFlow and Keras.

Architecture:

* Input Layer: 64 neurons
* Hidden Layer: 16 neurons with ReLU activation
* Output Layer: 10 neurons with Softmax activation

Compilation Settings:

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Metric: Accuracy

---

## Task 4 — Train and Evaluate

Trained the model for:

* 30 epochs
* Batch size of 8

Results:

* Test Accuracy: Approximately 96%
* Test Loss: Approximately 0.14

Observation:

* The model achieved high accuracy with slight overfitting.
* Validation accuracy remained close to training accuracy, indicating good generalization.

---

## Task 5 — Plot Training Accuracy

Visualized:

* Training Accuracy
* Validation Accuracy

Using:

* Matplotlib

Purpose:

* Monitor model performance
* Detect overfitting behavior

---

# Technologies Used

* Python
* Google Colab
* TensorFlow / Keras
* Scikit-learn
* Pandas
* Matplotlib

---

# Repository Structure

```bash
├── Artificial_Intelligence_Lab_Assignment.ipynb
├── README.md
```

---

# How to Run

1. Open the notebook in Google Colab
2. Install required libraries if needed
3. Run all cells sequentially

---

# Open in Colab

You can open the notebook directly in Google Colab using the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_NOTEBOOK_LINK)

Replace `YOUR_NOTEBOOK_LINK` with your notebook URL after uploading it to GitHub.

---

# Author

Mohab Ahmed
