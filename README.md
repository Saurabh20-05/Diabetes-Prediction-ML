# 🩺 Diabetes Prediction using Support Vector Machine (SVM)

This project uses **Support Vector Machine (SVM)** to predict whether a person is **diabetic** or **non-diabetic** based on various medical factors.  
The model is trained on the **PIMA Indians Diabetes Dataset**, a widely used dataset available on the **UCI Machine Learning Repository** and **Kaggle**.  
It analyzes patient health data such as glucose level, BMI, age, and more to predict diabetes risk levels.

---

## 📘 Project Overview
This Python project demonstrates a **binary classification** problem in healthcare.  
By analyzing health metrics, the model predicts diabetes likelihood using a **linear kernel SVM classifier**.  
It standardizes the dataset, splits it into training and testing subsets, and evaluates performance using accuracy metrics.

---

## 🗂️ Dataset Information
- **Name:** PIMA Indians Diabetes Dataset  
- **Source:** UCI Machine Learning Repository / Kaggle  
- **Format:** CSV file with 768 entries and 9 columns  

**Description:**
- The dataset contains medical test values along with a binary outcome (0 or 1).  
  - **0 → Non-Diabetic**  
  - **1 → Diabetic**

**Features include:**
- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

---

## 🧠 Technologies Used
- Python 3.x  
- NumPy  
- Pandas  
- Scikit-learn  

---

## ⚙️ Project Workflow
1. **Load the dataset** using Pandas  
2. **Explore and understand the data** using `.head()`, `.shape`, and `.groupby()`  
3. **Separate features and labels**
4. **Standardize the data** using `StandardScaler`  
5. **Split** the dataset into training (80%) and testing (20%) sets  
6. **Train** the SVM model:
7. **Evaluate** model performance using accuracy metrics  
8. **Make predictions** for new data to determine diabetes status  

---

## 📊 Example Output
Accuracy of training data: 0.79
Accuracy of testing data: 0.77
Person is Non Diabetic

---

## 🧪 Predicting Custom Input

You can edit the input tuple to test your own data:
input_data = (1, 103, 30, 38, 83, 43.3, 0.183, 33)

The model output:
Person is Non Diabetic

## 👨‍💻 Author
Developed by **Saurabh**  
Feel free to connect or contribute to this project!

---

⭐ If you found this project helpful, don't forget to **star** the repository!
