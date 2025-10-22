# Semiconductor Wafer Defect Classification using CNN

A project that classifies semiconductor wafer map defects using **Convolutional Neural Networks (CNN)** built with **TensorFlow and Keras**.  
This model automatically detects and categorizes wafer defects such as *Center, Donut, Edge-Loc, Edge-Ring, Loc, Near-Full, Random, Scratch,* and *None*, enabling improved semiconductor yield analysis.


## Project Overview

Semiconductor manufacturing wafers often contain various defect patterns that can affect yield and performance.  
This project leverages **CNN-based image classification** to automate the defect identification process using the **WM-811K Wafer Map Dataset**.


## Dataset 

 - WM-811K Wafer Map Dataset
 - [DATASET](http://mirlab.org/dataset/public/).

## Results

| Metric | Value |
|---------|--------|
| **Training Accuracy** | 95.6% |
| **Validation Accuracy** | 93.2% |
| **Test Accuracy** | 92.79% |
| **Test Loss** | 0.22 |

**Classification Report:**

| Metric | Score |
|---------|--------|
| Precision | 0.93 |
| Recall | 0.93 |
