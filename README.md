# ❤️ Heart Explainable AI

An Explainable Artificial Intelligence (XAI) project that demonstrates how Machine Learning and Deep Learning models can be interpreted for heart disease prediction using Decision Tree visualization and SHAP (SHapley Additive exPlanations).

---

## 📖 Overview

Artificial Intelligence models often behave like "black boxes", making it difficult to understand how predictions are made. This project applies Explainable AI techniques to provide transparency and interpretability for heart disease prediction models.

### Features

- Random Forest model interpretation
- Decision Tree visualization
- Deep Learning model explanation
- SHAP feature attribution analysis
- Global and local model explanations

---

## 🎯 Objectives

- Understand how ensemble learning models make decisions.
- Visualize individual decision trees within a Random Forest.
- Explain Deep Learning predictions using SHAP values.
- Identify the most influential features affecting heart disease predictions.
- Improve trust and transparency in healthcare AI systems.

---

## 📂 Project Structure

```text
Heart-Explainable-AI/
│
├── heart_dataset.csv
├── ml_model.pkl
├── dl_model.pkl
├── Heart_Explainable_AI.ipynb
├── README.md
└── requirements.txt
```

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- SHAP
- Matplotlib
- Jupyter Notebook

---

## 🤖 Machine Learning Model

The project uses a Random Forest Classifier for heart disease prediction. Individual decision trees can be visualized to better understand model behavior.

---

## 🧠 Deep Learning Model

A pretrained PyTorch model is loaded from `dl_model.pkl` and explained using SHAP.

---

## 🔍 Explainable AI with SHAP

SHAP (SHapley Additive exPlanations) is used to explain model predictions.

### Local Explanation
Explains a single prediction and shows how each feature contributes to the outcome.

### Global Explanation
Identifies the most influential features across multiple samples.

---

## 📊 Visualizations

- Decision Tree Visualization
- SHAP Force Plot
- SHAP Summary Plot

---

## ⚙️ Installation

```bash
pip install pandas numpy matplotlib scikit-learn torch shap tqdm ipywidgets
```

---

## ▶️ Running the Project

```bash
jupyter notebook
```

Open:

```text
Heart_Explainable_AI.ipynb
```

Run all cells sequentially.

---

## ⚠️ Common Issues

### Scikit-learn Version Warning

```bash
pip install scikit-learn==1.5.1
```

### Missing PyTorch

```bash
pip install torch
```

### Missing SHAP

```bash
pip install shap
```

### Missing tqdm

```bash
pip install tqdm
```

---

## 🎓 Learning Outcomes

- Interpret Random Forest models.
- Visualize Decision Trees.
- Explain Deep Learning predictions.
- Apply SHAP to healthcare datasets.
- Build transparent and trustworthy AI systems.

---

## 👨‍💻 Author

**ANG SEE SIANG**

---

## 📜 License

This project is intended for educational and academic purposes.
