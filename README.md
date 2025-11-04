# Heart-disease-prediction
Heart Disease Prediction using Logistic Regression (Machine Learning Project)
# ❤️ Heart Disease Prediction using Logistic Regression

### 📘 Overview
This project predicts the likelihood of **Heart Disease** in a person based on multiple medical attributes.  
It uses **Logistic Regression**, a supervised Machine Learning algorithm, to classify whether a person is at risk of heart disease or not.  
The project is implemented in **Python** and presented as an interactive web app using **Streamlit**.

---

### 🧠 Key Features
- Machine Learning model trained using Logistic Regression  
- Scaler applied for normalized and accurate predictions  
- Clean, simple and interactive Streamlit UI  
- Medical information table with normal ranges  
- Real-time result display with health tips  

---

### ⚙️ Tech Stack
- **Python 3.x**
- **Pandas**, **NumPy**, **Scikit-learn**
- **Streamlit**
- **Pickle**

---

### 🩺 Dataset Description
The dataset contains 14 important features that are used to determine the presence of heart disease.  
Below is a short explanation of each parameter:

| Feature | Description |
|----------|--------------|
| **age** | Age of the person (in years) |
| **sex** | 1 = Male, 0 = Female |
| **cp** | Chest Pain Type (0–3) |
| **trestbps** | Resting Blood Pressure (mm Hg) |
| **chol** | Serum Cholesterol (mg/dl) |
| **fbs** | Fasting Blood Sugar > 120 mg/dl (1 = True, 0 = False) |
| **restecg** | Resting ECG Results (0–2) |
| **thalach** | Maximum Heart Rate Achieved |
| **exang** | Exercise Induced Angina (1 = Yes, 0 = No) |
| **oldpeak** | ST Depression induced by exercise |
| **slope** | Slope of the ST Segment (0–2) |
| **ca** | Number of Major Vessels (0–3) |
| **thal** | Thalassemia (0 = Normal, 1 = Fixed Defect, 2 = Reversible Defect) |
| **target** | 1 = Heart Disease Present, 0 = No Disease |

---

### 💻 How to Run the Project Locally

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/heart-disease-prediction.git
   cd heart-disease-prediction

2. Install dependencies
pip install -r requirements.txt

3.Run the Streamlit app
streamlit run app.py

4.The app will open in your browser at
👉 http://localhost:8501
