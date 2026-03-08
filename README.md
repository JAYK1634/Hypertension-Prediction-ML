# Hypertension Stage Prediction System (Machine Learning)

## Overview

This project presents a **Machine Learning based system for predicting hypertension stages using patient health data**. The system analyzes various medical attributes such as age, symptoms, medical history, and blood pressure measurements to classify the stage of hypertension.

The project demonstrates how machine learning models can be integrated with a web application to provide an interactive prediction tool that can assist in monitoring and understanding hypertension risk.

The system consists of two main components:

1. **Machine Learning Model** – trained using patient datasets to learn patterns related to hypertension.
2. **Flask Web Application** – provides a user-friendly interface where users can input patient details and obtain prediction results.

---

## Project Structure

```
Hypertension-Prediction-ML
│
├── app.py               # Flask web application
├── forms.py             # Input form definitions
├── model.ipynb          # Model training and experimentation
├── model.joblib         # Saved trained ML model
├── requirements.txt     # Python dependencies
│
├── data/
│   ├── patient_data.csv
│   └── patient_data1.csv
│
├── templates/
│   ├── layout.html
│   ├── home.html
│   └── predict.html
│
├── static/
│   └── favicon.png
```

---

## Installation

### 1. Clone the repository

```
git clone https://github.com/JAYK1634/Hypertension-Prediction-ML.git
cd Hypertension-Prediction-ML
```

### 2. Install required dependencies

```
pip install -r requirements.txt
```

---

## Running the Application

Start the Flask server:

```
python app.py
```

After running the server, open your browser and visit:

```
http://127.0.0.1:5000
```

You can then enter patient health information in the web interface to obtain hypertension stage predictions.

---

## Machine Learning Workflow

The machine learning pipeline follows these stages:

1. **Data Collection**

   * Patient datasets containing medical and lifestyle attributes.

2. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical features
   * Preparing input features for training

3. **Model Training**

   * Training classification algorithms on the dataset.

4. **Model Evaluation**

   * Evaluating performance using metrics such as:

     * Accuracy
     * Precision
     * Recall
     * F1-score

5. **Model Deployment**

   * The trained model is saved using Joblib.
   * The model is integrated into a Flask web application for real-time predictions.

---

## Technologies Used

* Python
* Flask
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Joblib

---

## Key Features

* Machine learning based hypertension stage prediction
* Data preprocessing and analysis pipeline
* Model evaluation using standard performance metrics
* Interactive web interface for prediction
* Integration of trained ML model with Flask backend

---

## Future Improvements

* Incorporating additional patient health indicators
* Improving prediction accuracy with advanced ML models
* Deploying the application to a cloud platform
* Adding data visualization for prediction insights

---

## Author
**Jay Kumawat**
Information Technology Student
Vishwakarma Institute of Technology
