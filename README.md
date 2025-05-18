# 🏥 Machine Learning-Based Disease Prediction System

A robust Django-based application that predicts diseases based on user-reported symptoms using machine learning classification algorithms. This system aims to assist healthcare professionals and patients in early disease detection.

---

## 📌 Table of Contents

* [Project Overview](#project-overview)
* [Features](#features)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Model Evaluation](#model-evaluation)
* [Future Enhancements](#future-enhancements)
* [Contributing](#contributing)

---

## 🩺 Project Overview

The Disease Prediction System leverages multiple machine learning classifiers (like Decision Tree, Random Forest, Naive Bayes, SVM) to predict diseases based on user-reported symptoms. The system analyzes symptom patterns and classifies the likely disease, supporting early diagnosis and treatment recommendations.

---

## ✨ Features

* **Symptom-based Disease Prediction:** Input symptoms via the web interface and receive the predicted disease.
* **Multiple Classifiers:** Utilizes various machine learning models for higher prediction accuracy.
* **Data Storage:** Uses SQLite3 as the backend database to store symptom data and predictions.
* **User-Friendly Interface:** An intuitive and interactive UI built using Django for seamless interaction.
* **Model Evaluation:** Comprehensive performance metrics, including accuracy, precision, and recall.

---

## 📊 Dataset

The dataset consists of symptom-disease mappings collected from reliable medical sources. The data structure includes:

* **Symptoms:** Binary representation (presence/absence) for each patient.
* **Disease Labels:** The corresponding disease associated with the symptom set.

The data has been preprocessed to manage missing values and convert categorical data for model training.

---

## 🛠️ Technologies Used

* **Backend:** Django, SQLite3
* **Machine Learning Libraries:** scikit-learn, pandas, numpy
* **Frontend:** HTML, CSS, Bootstrap
* **Deployment:** Django's development server
* **Others:** Python 3.x for scripting and backend logic

---

## 💻 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/dev28616/Machine-Learning-Based-Disease-Prediction-System.git
cd Machine-Learning-Based-Disease-Prediction-System
```

2. **Create and activate a virtual environment:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Run migrations to set up the database:**

```bash
python manage.py migrate
```

5. **Create a superuser to access the Django admin panel:**

```bash
python manage.py createsuperuser
```

6. **Start the Django development server:**

```bash
python manage.py runserver
```

7. **Access the application:**

Open your browser and navigate to:

```
http://127.0.0.1:8000/
```

8. **Admin Panel Access:**
   Login to the admin interface using the superuser credentials:

```
http://127.0.0.1:8000/admin/
```

---

## 🚀 Usage

* **Disease Prediction:** Enter your symptoms through the UI and receive predictions instantly.
* **Admin Management:** Use the Django admin panel to manage users, data, and logs.
* **Data Persistence:** All predictions and inputs are stored securely in the SQLite3 database.

---

## 📈 Model Evaluation

The project incorporates various machine learning classifiers to predict diseases accurately. Models are evaluated based on:

* **Accuracy:** Proportion of correct predictions.
* **Precision:** Ratio of correctly predicted positive observations.
* **Recall:** Ratio of correctly predicted actual positives.
* **F1-Score:** Harmonic mean of precision and recall.

These metrics ensure the model's reliability and robustness when deployed.

---

## 🔮 Future Enhancements

* **Model Optimization:** Integrate hyperparameter tuning for improved accuracy.
* **API Integration:** Expose predictions through a RESTful API for external applications.
* **Enhanced Frontend:** Improve the UI for better user engagement and interactivity.
* **Database Expansion:** Support for additional diseases and more comprehensive symptom sets.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and open a pull request to suggest improvements or bug fixes.
