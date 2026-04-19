# 🧠 Perceptron from Scratch: The Geometry of Logic

This project is a fundamental implementation of the **Perceptron Algorithm** using Python and NumPy. It demonstrates how a single neuron can learn to classify data points by finding the perfect decision boundary in 3D space.

## 🚀 The Goal
To build a 3-input **OR Gate** classifier from scratch. Instead of using high-level libraries like Scikit-Learn or TensorFlow, I implemented the mathematical "Update Rule" manually to understand how AI actually learns.

## 🛠️ Key Concepts Implemented
- **Data as Geometry:** Representing logic gates as points in a 3D coordinate system.
- **Weights & Bias:** Initializing and adjusting the parameters that define the decision plane.
- **Activation Function:** Using the `Sign` function (mapping 0 to -1) for clear classification.
- **The Learning Loop:** Iterative error correction (Epochs) until the model reaches **Zero Error**.

## 📊 How it Works
1. **Initialize** weights with random values.
2. **Forward Pass:** Calculate the dot product $y = x \cdot w + b$.
3. **Compare:** Check if the prediction matches the actual label.
4. **Update:** Adjust weights using the rule: $w = w + (\alpha \cdot error \cdot x)$.

## 🏁 Result
The model successfully converges, finding the exact weights and bias needed to separate the "True" and "False" regions of the OR gate.

---
*Created as part of my journey into Deep Learning Foundations.*
