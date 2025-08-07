#  Virtual Health Care Assistant

## 📌 Project Overview

The **Virtual Health Care Assistant** is an AI-powered backend service designed to assist users with **health consultations**, **real-time diagnosis**, and **appointment scheduling**. The system securely stores medical data, integrates ML-based diagnosis suggestions, and connects users with doctors in real-time. It is built for scalability and privacy-first healthcare interactions.


## 🚀 Key Features

- 🧠 AI-based symptom analysis and preliminary diagnosis
- 📅 Appointment scheduling with doctors or clinics
- 🔐 Encrypted and secure storage of patient health data
- ⏱️ Real-time response integration using REST APIs
- 💬 Support for patient interaction and consult logs

---

## 🧠 Technologies Used

- **Python 3.10+**
- **Flask / FastAPI** – Backend API development
- **Scikit-learn / TensorFlow** – AI-based diagnosis models
- **PostgreSQL / SQLite** – Secure health data storage
- **JWT / OAuth** – For user authentication
- **Docker** – For containerized deployment
- **Postman** – API testing and validation

---


## ⚙️ How It Works

1. **User Login/Register** – Authenticated securely using JWT tokens.
2. **Symptom Input** – Patient submits symptoms or health queries.
3. **AI Diagnosis** – Backend model returns potential health conditions.
4. **Appointment Booking** – Users can schedule consults with verified doctors.
5. **Storage** – All user data and logs are securely saved in the database.

---

### ✅ Setup Environment

pip install -r requirements.txt
Run Backend Server :
uvicorn api.main:app --reload  # for FastAPI
# OR
python api/main.py             # for Flask
API will be available at: http://127.0.0.1:8000/

## Sample Output Pictures

![VH 1](https://raw.githubusercontent.com/Bhavanaviswanath/Virtual-health-Care-Assistant/4d50bd9dcc0eaea0f15ab7958b5521ef9cd8901a/VH1.png)

![VH 2](https://raw.githubusercontent.com/Bhavanaviswanath/Virtual-health-Care-Assistant/4d50bd9dcc0eaea0f15ab7958b5521ef9cd8901a/VH2.png)


##  👥 Author
Natuva Bhavana 

📧 natuvabhavana@gmail.com
