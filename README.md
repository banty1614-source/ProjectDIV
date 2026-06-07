# 🎓 Student Performance Predictor

> My first Machine Learning project built using Python and Scikit-learn.

## 📌 Project Overview

The objective of this project is to predict whether a student will **Pass** or **Fail** based on various academic performance indicators. This project helped me understand the complete machine learning workflow, from data preprocessing to model evaluation.

---

## 🚀 Features

* Predicts student performance (**Pass / Fail**)
* Uses a **Decision Tree Classifier**
* Splits data into training and testing sets
* Evaluates model performance using **Accuracy Score**
* Demonstrates the complete supervised learning pipeline

---

## 📊 Dataset Features

| Feature       | Description                             |
| ------------- | --------------------------------------- |
| StudyHours    | Number of hours studied                 |
| Attendance    | Attendance percentage                   |
| Assignments   | Number of assignments completed         |
| PreviousMarks | Marks obtained in previous examinations |

### 🎯 Target Variable

```text
Result → Pass / Fail
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Anaconda

---

## 🧠 Machine Learning Concepts Applied

* Supervised Learning
* Classification
* Features and Labels
* Train-Test Split
* Decision Trees
* Model Training (`fit`)
* Prediction (`predict`)
* Model Evaluation using Accuracy Score

---

## ⚙️ Workflow

```text
Load Dataset
      ↓
Separate Features (X) and Labels (Y)
      ↓
Train-Test Split
      ↓
Train Decision Tree Model
      ↓
Make Predictions
      ↓
Evaluate Accuracy
```

---

## 📈 Model Performance

The Decision Tree Classifier achieved an accuracy of:

```text
95.24%
```

on the testing dataset.

---

## 📂 Project Structure

```text
student-performance-predictor/
│
├── ProjectDIV.ipynb
├── students_data.csv
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/student-performance-predictor.git
```

2. Navigate to the project directory:

```bash
cd student-performance-predictor
```

3. Install the required libraries:

```bash
pip install pandas numpy scikit-learn jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `ProjectDIV.ipynb` and run all cells.

---

## 💡 Sample Prediction

### Input

```text
Study Hours    : 5
Attendance     : 88
Assignments    : 8
Previous Marks : 72
```

### Predicted Output

```text
Pass
```

---

## 🌱 Learning Outcomes

Through this project, I learned:

* How machine learning models learn patterns from data.
* The difference between features and labels.
* The importance of splitting data into training and testing sets.
* How Decision Trees make predictions.
* How to evaluate classification models using accuracy.

---

## 🔮 Future Improvements

* Experiment with Random Forest Classifier.
* Evaluate the model using Precision, Recall, and F1 Score.
* Increase dataset size for better generalization.
* Deploy the model using Streamlit.

---

## 👨‍💻 Author

**Banty Kumar**

Electrical Engineering Undergraduate at NIT Patna

Passionate about Machine Learning, Data Analytics, and building impactful projects.

---

⭐ If you found this project interesting, feel free to star the repository!
