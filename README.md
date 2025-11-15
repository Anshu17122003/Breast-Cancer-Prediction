# 🎗️ Binary Classification – Breast Cancer Detection

This repository contains a Jupyter Notebook implementing a **Binary Classification model** to detect breast cancer using machine learning.  
The project uses a local dataset **breast_cancer.csv**, which contains diagnostic measurements used to classify tumors as **benign** or **malignant**.

---

## 🚀 Project Overview

The goal of this project is to accurately classify breast tumors as:

- **Benign (non-cancerous)**  
- **Malignant (cancerous)**  

using multiple medical diagnostic features extracted from breast mass cell nuclei.

This notebook walks through:

- Loading and exploring the dataset  
- Preprocessing & normalization  
- Exploratory Data Analysis (EDA)  
- Building different classification models  
- Evaluating model performance  
- Visualizing results  

---

## 📂 Files in This Project

| File | Description |
|------|-------------|
| **Binary Classification - Breast Cancer Dataset.ipynb** | Complete machine learning workflow for breast cancer detection |
| **breast_cancer.csv** | Dataset containing diagnostic features and target classes |

---

## 📁 Dataset Description: `breast_cancer.csv`

The dataset includes the following:

- **Features:**  
  - Radius  
  - Texture  
  - Perimeter  
  - Area  
  - Smoothness  
  - Compactness  
  - Concavity  
  - Symmetry  
  - Fractal dimension  
  - …and more (depending on your CSV)

- **Target:**  
  - `0` → Malignant  
  - `1` → Benign  

Example of loading the dataset:

```python
import pandas as pd

df = pd.read_csv("breast_cancer.csv")
df.head()
