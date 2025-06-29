# 📊 Student Performance Predictor

A machine learning web application that predicts a student’s **Math score** based on their demographics and academic attributes. Built using **Python, Scikit-learn, Flask, HTML/CSS**, and **Docker**, this project simulates a real-world ML deployment pipeline with model optimization, API integration, and web-based UI.



---
## 📌 Introduction

This project is designed to predict the **Math score** of students using various input features like:

- Gender
- Ethnicity
- Parental level of education
- Lunch type
- Test preparation course
- Reading and Writing scores

The pipeline includes **data preprocessing, exploratory data analysis (EDA), model selection with GridSearchCV**, and deployment using **Flask** and **Docker**.

📚 Dataset: [Kaggle - Student Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)


---
## 🚀 Features

✅ **Regression Model** to predict student scores  
📈 **Model Optimization** with GridSearchCV across 8 algorithms  
🧠 **Multiple Regressors** including Random Forest, XGBoost, Ridge, Lasso, and CatBoost  
📊 **EDA Visualizations** with Matplotlib and Seaborn  
🖥️ **Interactive Web UI** built with Flask and Bootstrap  
🐳 **Dockerized App** for cloud-ready deployment  
💡 **CI/CD Ready** for platforms like AWS or Render  

---

## 🔎 How It Works

1. **User Input:** Enter student demographics and scores through a form  
2. **Preprocessing:** Input is encoded and scaled as required  
3. **Model Prediction:** ML model estimates math score based on trained patterns  
4. **Output:** Displayed in the browser with prediction result  

---


## 🛠️ Technologies Used

| Category        | Tools/Frameworks                                   |
|------------------|----------------------------------------------------|
| Language         | Python 3.10                                        |
| ML Libraries     | Scikit-learn, XGBoost, CatBoost                    |
| Data & Viz       | Pandas, NumPy, Matplotlib, Seaborn                |
| Web Framework    | Flask, Jinja2 Templates, Bootstrap 5              |
| Containerization | Docker                                             |
| Tools            | Git, GitHub, VS Code                              |

---


## 📊 Model Performance

| Metric      | Value      |
|-------------|------------|
| R² Score    | 88.06%     |
| RMSE        | 5.39       |
| Best Model  | Ridge Regressor (via GridSearchCV) |

---

## 👩‍💻 Contributing
Contributions and suggestions are welcome!
Feel free to fork the repo, open issues, or submit pull requests.
