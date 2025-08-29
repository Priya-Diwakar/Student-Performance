# Student Performance Prediction Dashboard

An interactive Streamlit dashboard that predicts student performance based on study habits, sleep, extracurricular activities, and practice using a trained ML model.

---

## Features

- **User Input Panel:** Enter hours studied, previous scores, extracurricular activities, sleep hours, and sample papers practiced.
- **Performance Prediction:** Predicts student performance index using a trained Linear Regression model.
- **Data Visualizations:**
  - Correlation heatmap
  - Scatter plots of features vs performance
  - Distribution plot with predicted value
  - Input effect plot showing how changes in inputs affect performance

---

## Technologies Used

- Python 3.11
- Streamlit
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Joblib

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/YourUsername/StudentPerformanceApp.git
cd StudentPerformanceApp
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Run the Streamlit app:

bash
Copy code
streamlit run app.py
The dashboard will open in your default browser.

Files
app.py – Main Streamlit application

Student_Performance.csv – Dataset

student_performance_model.joblib – Trained ML model

requirements.txt – Project dependencies

