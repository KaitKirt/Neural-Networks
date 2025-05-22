# 🧠 Neural Networks for Character Recognition

**Author**: Kaitlyn Kirt  
**Course**: CMOR 220  
**Term**: Spring 2024  
**Project**: Neural Networks - Pattern Recognition  
**Last Modified**: April 26, 2024  

---

## 📋 Overview

This project builds a **basic neural network** from scratch using NumPy to recognize letters represented as binary vectors. It simulates recognizing noisy versions of the letters **R, I, C, and E** using a feedforward neural network with sigmoid activations.

---

## 📂 Files

- `Project11.ipynb`: The main Jupyter Notebook implementing all logic for training and testing the neural network.
- `README.md`: Description and instructions for running the project.

---

## 🔍 Techniques Used

- 🧮 **Feedforward Neural Network** with:
  - One hidden layer
  - Manual backpropagation
- 🎯 Binary classification using **2-bit target outputs**
- 🧪 Repeated testing with **noisy letter variants** via random bit flips
- 📊 Visualization of the letter patterns as 5x5 binary matrices

---

## 🛠️ Requirements

```bash
pip install numpy matplotlib
