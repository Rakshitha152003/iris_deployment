# 🌸 Iris Flower Classification & Deployment

## 📌 Project Overview

The Iris Flower Classification project is a Machine Learning application that predicts the species of an Iris flower based on its physical measurements.

The application takes four input features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

Using a pre-trained Machine Learning classification model, the application predicts whether the flower belongs to one of the following three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The trained model is saved as a Pickle file (`model.pkl`) and integrated into a Streamlit web application to provide real-time predictions through a simple user interface.

## 🎯 Project Objectives

- Understand the end-to-end Machine Learning workflow.
- Perform classification using the Iris dataset.
- Train and save a Machine Learning model.
- Integrate the trained model into a Streamlit application.
- Deploy the application to make predictions through a web interface.

## 📊 Dataset Description

The Iris dataset is a popular dataset used for understanding and implementing classification algorithms.

It contains 150 observations belonging to three different Iris flower species.

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal in cm |
| Sepal Width | Width of the sepal in cm |
| Petal Length | Length of the petal in cm |
| Petal Width | Width of the petal in cm |
| Target | Iris flower species |

**Target Classes:**
1. Setosa
2. Versicolor
3. Virginica

## ⚙️ Technologies Used

- Python – Programming language
- Pandas – Data handling and manipulation
- NumPy – Numerical operations
- Scikit-learn – Machine Learning model
- Pickle – Model serialization
- Streamlit – Web application development
- Git & GitHub – Version control and project hosting

## 🔄 Project Workflow

The project follows an end-to-end Machine Learning deployment workflow.

**Step 1: Data Collection**
- Loaded the Iris dataset.
- Identified input features and target variable.

**Step 2: Data Preprocessing**
- Checked the dataset structure.
- Separated independent and dependent variables.
- Prepared the dataset for model training.

**Step 3: Model Training**
- Developed a classification model using Scikit-learn.
- Trained the model using the Iris dataset.

**Step 4: Model Serialization**
- Saved the trained model using Pickle.
- Stored the model as `model.pkl` for future predictions.

**Step 5: Application Development**
- Created an interactive interface using Streamlit.
- Designed four numerical input fields.
- Implemented a Predict button to generate predictions.

**Step 6: Model Integration**
- Loaded the saved model into the Streamlit application.
- Passed the user-provided measurements to the model.
- Displayed the predicted flower species.

**Step 7: Deployment**
- Prepared the application and dependencies for deployment.
- Made the prediction interface accessible through a web application.

## 📁 Project Structure

```text
iris_deployment/
│
├── app.py
│
├── model.pkl
│
├── requirements.txt
│
└── README.md
```

## 🚀 How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Rakshitha152003/iris_deployment.git
```

### 2. Navigate to the Project Directory

```bash
cd iris_deployment
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**
```bash
venv\Scripts\activate
```

**Mac/Linux:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
pip install streamlit
```

### 5. Run the Application

```bash
streamlit run app.py
```

The application will open in your default browser.

## 🖥️ Application Features

- Simple and interactive user interface.
- Four numerical input fields for flower measurements.
- Real-time classification predictions.
- Three possible Iris flower classifications.
- Pre-trained Machine Learning model integration.

## 🔮 Future Enhancements

- Add model performance evaluation and visualization.
- Compare multiple classification algorithms.
- Display prediction probabilities.
- Implement input validation and error handling.
- Deploy the application using Streamlit Community Cloud.
- Integrate MLflow for experiment tracking and model management.
- Implement Docker for containerization.
- Introduce model monitoring and data drift detection.

## 👩‍💻 Author

**Madishetti Rakshitha**

B.Tech Graduate (2022–2026)

Currently Pursuing Data Science Training at Innomatics Research Labs.

**Technical Interests:**
- Machine Learning
- Data Analytics
- Python Programming
- Model Deployment
- MLOps

### 🔗 Connect With Me

GitHub: https://github.com/Rakshitha152003
