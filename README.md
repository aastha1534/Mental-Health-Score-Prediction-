# Mental Health Score Predictor

A machine learning project that predicts a **mental health impact score** for students based on their social media usage patterns. The project includes a trained ML model, a Jupyter Notebook covering the full data analysis workflow, and a simple web interface to interact with the model.

## 📌 Overview

This project analyzes the relationship between student social media habits and mental well-being, using a trained model to estimate a mental health score from user inputs.

## 🗂️ Project Structure

```
├── main.py                                              # Backend script to run/serve the model
├── ML_Project.ipynb                                     # Jupyter Notebook: data cleaning, EDA, model training
├── ML Project.html                                      # HTML export of the notebook
├── Mental_Health_Model.pkl                              # Trained ML model (pickle file)
├── Student Social Media And Mental Health Impact.csv    # Dataset used for training
├── index.html                                           # Web app frontend
├── style.css                                            # Frontend styling
├── script.js                                            # Frontend logic
└── requirements.txt                                     # Python dependencies
```

## ⚙️ Setup & Installation

1. Clone the repository:
   ```
   git clone https://github.com/aastha1534/Mental-Health-Score.git
   cd Mental-Health-Score
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the application:
   ```
   python main.py
   ```
4. Open `index.html` in your browser to use the interface.

## 📊 Dataset

The model is trained on `Student Social Media And Mental Health Impact.csv`, which contains survey data on student social media habits and self-reported mental health indicators.

## 🧠 Model

The trained model is stored as `Mental_Health_Model.pkl`. Full training steps, exploratory data analysis, and evaluation are documented in `ML_Project.ipynb`.

## 🖥️ Web Interface

A lightweight frontend (`index.html`, `style.css`, `script.js`) allows users to input their social media habits and receive a predicted mental health score.

## 🚀 Future Improvements

- Add model performance metrics and visualizations
- Improve UI/UX of the web interface
- Deploy as a live web app

## 📄 License

This project is for educational purposes.
