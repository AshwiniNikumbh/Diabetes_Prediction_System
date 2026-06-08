# 🩺 Diabetes Prediction System using Machine Learning

A Machine Learning based web application that predicts whether a person is diabetic or not based on various health parameters. The application is developed using **Python**, **Streamlit**, and **Scikit-Learn**.

## 📌 Project Overview

Diabetes is one of the most common chronic diseases worldwide. Early detection can help in proper treatment and prevention of complications.

This project uses a trained Machine Learning model to predict diabetes based on medical attributes such as:

- Number of Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI
- Diabetes Pedigree Function
- Age

The application provides an easy-to-use web interface where users can enter their health details and instantly receive a prediction result.

---

## 🚀 Features

✅ User-friendly Streamlit web interface

✅ Real-time diabetes prediction

✅ Machine Learning model integration

✅ Simple and responsive design

✅ Fast prediction results

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-Learn
- NumPy
- Pickle
- Streamlit Option Menu

---

## 📂 Project Structure

```text
Diabetes_Prediction_System/
│
├── Dataset/
│
├── Images/
│
├── Notebook/
│   └── DiabetesExploration.ipynb
│
├── savedModels/
│   └── Diabetes.sav
│
├── diseasePred.py
├── diabetes values.txt
├── requirements.txt
└── README.md
```

---

## 📊 Input Parameters

The model accepts the following inputs:

| Parameter | Description |
|------------|------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| Blood Pressure | Diastolic blood pressure |
| Skin Thickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| Diabetes Pedigree Function | Diabetes hereditary likelihood |
| Age | Age of the person |

---

## 🖥️ Application Screenshots

### Home Screen

![Home Screen](Images/home.png)

### Prediction Result

![Prediction Result](Images/result.png)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/AshwiniNikumbh/Diabetes_Prediction_System.git
```

### 2️⃣ Navigate to Project Directory

```bash
cd Diabetes_Prediction_System
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
streamlit run diseasePred.py
```

---

## 📦 Required Libraries

```text
numpy>=1.22.4
pickle-mixin==1.0.2
streamlit==1.2.0
streamlit-option-menu==0.3.2
scikit-learn==1.0.1
```

---

## 🔍 How It Works

1. User enters health-related details.
2. Input data is passed to the trained Machine Learning model.
3. The model processes the data and predicts:
   - Diabetic
   - Not Diabetic
4. The result is displayed instantly on the screen.

---

## 🎯 Future Enhancements

- Add Heart Disease Prediction
- Add Parkinson's Disease Prediction
- Improve UI/UX Design
- Deploy on Streamlit Cloud
- Add data visualization dashboard
- Improve model accuracy with advanced algorithms

---

## 👩‍💻 Team Members

- Ashwini Nikumbh
- Devyani
- Mansi
- Khushbu

---

## 📄 License

This project is developed for educational and learning purposes.

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
