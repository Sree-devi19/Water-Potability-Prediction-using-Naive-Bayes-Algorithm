# 💧 Water Potability Prediction using Naive Bayes

This repository contains a machine learning project that uses a **Naive Bayes classifier** to predict whether a sample of water is **potable (safe to drink)** or not, based on various chemical and physical properties.

---

## 📘 Project Overview

**Goal:** Classify water samples as *potable* or *not potable*  
**Model Used:** Gaussian Naive Bayes  
**Dataset:** Any appropriate dataset form external source

---

## 🧪 Features in the Dataset

- `ph` – PH of water (0 to 14)
- `Hardness` – Hardness of water
- `Solids` – Total dissolved solids in ppm
- `Chloramines` – Amount of Chloramines in ppm
- `Sulfate` – Sulfate content in mg/L
- `Conductivity` – Electrical conductivity in μS/cm
- `Organic_carbon` – Organic carbon in ppm
- `Trihalomethanes` – Concentration in μg/L
- `Turbidity` – Turbidity in NTU
- `Potability` – Target (0: Not potable, 1: Potable)

---

## 🔍 Key Steps

- Load and inspect the dataset
- Handle missing values
- Feature scaling (if needed)
- Split dataset into training/testing
- Train **Naive Bayes classifier**
- Evaluate using accuracy, confusion matrix.
