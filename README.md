# 🎓 Student Placement Predictor

## 🌐 Live Demo

👉 Try the application here:  
🔗 live demo: https://render-first-ml-project.onrender.com/

---

## 🚀 Project Overview

This project is a simple machine learning web application built to understand the **complete workflow of training a model and using it in a real-world application**.

---

## 🎯 Project Objective

The main goal of this project is to learn:

- How to train a machine learning model  
- How to save the trained model  
- How to load and use the model in a web application  
- How to integrate machine learning with development using Flask  

---

## 🧠 Machine Learning Model

- Algorithm: Logistic Regression  
- Type: Binary Classification  
- Input Features:
  - CGPA  
  - IQ  
- Output:
  - 1 → Placed  
  - 0 → Not Placed  

---

## ⚙️ Workflow

1. Model training is done in the Jupyter Notebook (`student_placement.ipynb`)  
2. The trained model is saved as `model1.pkl`  
3. The Flask app (`app.py`) loads the trained model  
4. User inputs CGPA and IQ through the web interface  
5. The model predicts placement status  

---

## 🛠️ Tech Stack

- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Flask  
- HTML, CSS  

---

## 📁 Project Structure
```
student-placement-predictor/
│
├── templates/
│ └── index.html
│
├── student_placement.ipynb      # Model training
├── model1.pkl                   # Saved ML model
├── app.py                       # Flask application
├── requirements.txt
└── README.md
`````









