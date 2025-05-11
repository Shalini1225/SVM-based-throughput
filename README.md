# Cognitive Radio Spectrum Sensing with SVM - Throughput Optimization Project

This project demonstrates the application of **machine learning (SVM)** for enhancing wireless communication systems. It showcases how to optimize spectrum sensing in cognitive radio networks, which is a critical concept in modern communication and 5G systems. 

If you're a recruiter or engineer reviewing this project: it's about **smart spectrum management using energy-aware, data-driven classification techniques**—relevant to wireless systems, ML applications, embedded systems, and signal processing.

---

## 🧠 Problem Statement

Modern wireless networks face a **spectrum scarcity problem**. Cognitive radios attempt to solve this by using **unused licensed bands** without interfering with primary users. However, traditional binary classification (occupied vs. unoccupied) is too limiting.

---

## 💡 What I Built

I implemented a **multi-class classification model using SVM** to improve how cognitive radios decide when and how to transmit. The model:
- Considers **signal statistics and energy levels**.
- Trains on real-like simulation data.
- Optimizes for **throughput and low interference**.

---

## 🔍 Key Features

- 🧠 **SVM-Based Multi-Class Hypothesis**: Goes beyond traditional two-class models.
- 📈 **Energy-Aware Transmission**: Smarter decisions based on node battery levels.
- 📊 **Kernel Comparison**: Evaluates Linear, RBF, and Polynomial SVM kernels.

---

## 📊 Results

- **RBF Kernel** showed the highest accuracy (72%+) even in low-SNR conditions (-25 dB).
- Outperformed traditional methods in **throughput efficiency**.
- Demonstrated how **ML can drive smarter wireless communication decisions**.

---

## 🔁 How It Works

```text
Input Signal → Feature Extraction → Pd or Pf + Residual Energy
→ Train SVM Classifier → Predict Optimal Transmission Class

[![Read the Paper](https://img.shields.io/badge/Paper-View-blue)](https://ieeexplore.ieee.org/document/9788317/figures#figures)

