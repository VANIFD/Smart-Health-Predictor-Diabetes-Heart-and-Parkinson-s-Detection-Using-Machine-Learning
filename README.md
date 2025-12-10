# Smart Health Predictor

**Smart Health Predictor** is an interactive web application that uses Machine Learning models to predict the likelihood of **Diabetes**, **Heart Disease**, and **Parkinson's Disease** based on user input. The application is built using **Python**, **Streamlit**, and pre-trained ML models.

---

## Features

- **Diabetes Prediction:** Predicts if a person has diabetes based on health parameters like glucose level, BMI, age, etc.
- **Heart Disease Prediction:** Predicts the likelihood of heart disease based on patient data such as cholesterol, blood pressure, and ECG results.
- **Parkinson's Disease Prediction:** Detects Parkinson's disease using voice features and other speech-related measurements.
- **Interactive Interface:** Easy-to-use web interface for real-time predictions.

---

## Technologies Used

- **Python** – Programming language  
- **Streamlit** – For building the web application  
- **Scikit-learn** – For building and using ML models  
- **Pickle** – For saving and loading ML models  

---

## Installation

1. Clone the repository:

```bash
git clone <repository_url>

2. Navigate to the project folder:

cd <project_folder>

3. Install required packages:

pip install -r requirements.txt

4. Run the Streamlit app:

streamlit run main.py

project/
│
├── .venv/
│
├── colab_files_to_train_models/
│   ├── Multiple disease pre....ipynb
│   ├── Multiple disease pre....ipynb
│   └── Multiple disease pre....ipynb
│
├── dataset/
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
│
├── saved_models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
│
├── app.py
├── README.md
└── requirements.txt


