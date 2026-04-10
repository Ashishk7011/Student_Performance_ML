## End to End MAchine Learning Project#

## 📌 Overview

This project demonstrates a complete machine learning pipeline integrated with a Flask web application. It allows users to input data through a web interface and get predictions from a trained model.

---

## 🏗️ Project Structure

```
.
├── app.py
├── requirements.txt
├── setup.py
├── .gitignore
├── src/
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │   └── train_pipeline.py
│   ├── components/
│   ├── utils/
│   └── exception/
├── templates/
│   ├── index.html
│   └── home.html
└── artifacts/
```

---

## ⚙️ Features

* End-to-end ML pipeline
* Flask-based web app
* User input → Prediction → Display result
* Modular and production-ready structure

---

## 🔄 Workflow

1. User enters data in UI
2. Flask receives request
3. Data is converted into DataFrame
4. Prediction pipeline runs
5. Model returns output
6. Result displayed

---

## ▶️ How to Run

### 1. Clone Repository

```
git clone <repo-url>
cd <project-folder>
```

### 2. Create Virtual Environment

```
python -m venv venv
```

Activate:

```
venv\Scripts\activate   (Windows)
source venv/bin/activate (Mac/Linux)
```

---

### 3. Install Dependencies

```
pip install -r requirements.txt

```

---

### 3. Train Model and Pick Best Model 

```

python src\components\data_ingestion.py

```

---

### 5. Run App

```
python app.py
```

---

### 6. Open Browser

```
http://localhost:5000
```

---

## 📊 Input Features

* Gender
* Ethnicity
* Parental education
* Lunch type
* Test preparation
* Reading score
* Writing score

---

## 📦 Output

* Predicted score/result from ML model

---

## 📚 Tech Stack

* Python
* Flask
* Scikit-learn
* Pandas / NumPy
* XGBoost / CatBoost

---

## 🚀 Future Improvements

* Deploy using Docker / AWS
* Add MLflow tracking
* Improve UI
* Add REST API endpoints

---

## 👨‍💻 Author

* Ashish Kumar

---

## ⭐ Summary

This project combines:

* Machine Learning
* Backend Development
* Deployment concepts
