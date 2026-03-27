# Intelligent Robotics & AI System

### (CNN Image Classification + Autonomous Robot in Webots)

This project combines **Deep Learning (CNN)** and **Robotics (Webots simulation)** to demonstrate an intelligent system capable of perception and autonomous navigation.

---

## 🎯 Project Overview

The goal of this project is to integrate:

* 🧠 **Computer Vision (CNN - CIFAR-10)**
* 🤖 **Autonomous Robot Navigation (Webots)**

The system demonstrates how AI can be applied to robotics for **environment awareness and decision-making**.

---

## 🧠 Part 1: CNN Image Classification

### 📊 Dataset

* CIFAR-10 (60,000 images, 10 classes)
* Categories include: airplane, car, bird, cat, dog, etc.

### 🏗 Model Architecture

* Convolutional Layers (Conv2D)
* MaxPooling Layers
* Dense Layers
* Activation: ReLU
* Output: Softmax

### ⚙️ Techniques Used

* Image normalization
* Training & validation split
* Optimizer comparison (SGD vs Adam)
* Model evaluation using accuracy

### 📈 Outcome

* Successfully trained a CNN model for multi-class classification
* Demonstrated performance comparison between optimizers

---

## 🤖 Part 2: Autonomous Robot (Webots)

### 🧠 System Behavior

The robot operates using **sensor-based reactive control**:

* Detects obstacles using distance sensors
* Uses Braitenberg algorithm for navigation
* Captures RGB data from camera
* Performs autonomous movement

### 🔁 Control Logic

* If obstacle detected:

  * Move backward
  * Turn left
* Else:

  * Continue forward using Braitenberg algorithm

### 💡 Features

* Obstacle avoidance
* LED signaling
* Camera-based color detection
* Autonomous navigation

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* Webots Simulator
* NumPy
* Matplotlib
* Google Colab

---

## 🚀 How to Run

### CNN Model

1. Open `cnn_cifar10.ipynb` in Google Colab
2. Run all cells
3. View training results

### Webots Simulation

1. Open Webots
2. Load robot world
3. Attach controller (`main.py`)
4. Run simulation

---

## 📊 Key Learning Outcomes

* Deep Learning (CNN for image classification)
* Robotics simulation and control
* Sensor-based navigation
* Integration of AI with robotics systems

---

## 💡 Future Improvements

* Integrate CNN with robot camera (real-time vision)
* Add object detection instead of classification
* Implement SLAM or path planning
* Deploy on real robot hardware

---
BEng (Hons) Robotics & Artificial Intelligence

