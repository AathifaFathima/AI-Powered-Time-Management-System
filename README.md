# ⏱️ AI-Powered Time Management System

An intelligent time management application developed using Machine Learning, Python, and Streamlit.

## 📌 Project Overview

The AI-Powered Time Management System helps users organize tasks, estimate completion times, assess deadline risks, and generate personalized work schedules.

The application uses an XGBoost regression model to predict task completion time based on task characteristics and user preferences.

## 🚀 Features

- AI-Based Task Completion Time Prediction
- Deadline Risk Assessment
- Intelligent Task Prioritization
- Personalized Schedule Generation
- Personalized Task Recommendations
- Task Management System
- Interactive Analytics Dashboard
- Task Completion Tracking

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Plotly
- Joblib
- Google Colab
- Visual Studio Code

## 🤖 Machine Learning

The project includes:

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis
3. Feature Engineering
4. Multiple Regression Model Training
5. Hyperparameter Tuning
6. Model Evaluation
7. Task Completion Time Prediction

The prototype model was trained using synthetic task-completion data.

## 📂 Project Structure

```text
AI-Powered-Time-Management-System/
│
├── app.py
├── task_xgboost.json
├── task_preprocessor.pkl
├── task_features.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Powered-Time-Management-System.git
```

### 2. Install Dependencies

Use Python 3.13 in a virtual environment.

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
streamlit run app.py
```

## 📊 Application Modules

### Task Completion Prediction
Predicts the estimated time required to complete a task using an XGBoost regression model.

### Deadline Risk Assessment
Estimates deadline risk based on predicted completion time and available working time.

### Task Prioritization
Recommends task priority using predefined scoring rules.

### Personalized Scheduling
Creates work sessions and breaks based on predicted task duration and user preferences.

### Personalized Recommendations
Provides rule-based time management suggestions.

### Task Manager
Allows users to add, complete, and delete tasks.

### Analytics Dashboard
Visualizes task completion progress, category distribution, and priority distribution.

## ⚠️ Limitations

- The machine learning model uses synthetic training data.
- Deadline risk, scheduling, and recommendations are rule-based.
- Task Manager data is stored in Streamlit session state and is not permanently saved.

## 🔮 Future Enhancements

- Database Integration
- Calendar Integration
- Real-Time Notifications
- User Authentication
- Improved Personalized Scheduling
- Model Training with Real-World Data

## 👩‍💻 Project Type

Machine Learning and Artificial Intelligence Internship Project
