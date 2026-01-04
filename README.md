💼 Employee Salary Prediction Using Linear Regression

A simple machine learning web application that predicts an employee’s salary based on years of experience using a Linear Regression model, deployed with Flask.

📌 Project Description

This project demonstrates how a basic supervised machine learning model can be trained, saved, and integrated into a web application.
It covers the complete workflow from data loading to model prediction through a user interface.

🚀 Key Features

📈 Linear Regression model for salary prediction

🌐 Flask-based web application

💾 Model trained and saved using Pickle

🧩 Simple and easy-to-understand implementation

🛠️ Technologies Used

🐍 Python

📊 Scikit-learn

🌐 Flask

🧮 Pandas, NumPy

🎨 HTML
📂 Project Structure
Employee-Salary-Prediction/
│
├── 📁 data/
│   └── salary.csv              # Dataset used for training
│
├── 📁 model/
│   └── salary_model.pkl        # Saved machine learning model
│
├── 📁 notebook/
│   └── salary_regression.ipynb # Jupyter notebook for training
│
├── 📁 templates/
│   └── index.html              # HTML template
│
├── 🚀 app.py                   # Flask application
├── 📦 requirements.txt         # Required Python libraries
└── 📝 README.md                # Project documentation
⚙️ How It Works

👤 User enters years of experience

🧠 Input is sent to the trained Linear Regression model

📈 Model predicts the salary

🖥️ Result is displayed on the web page

▶️ Installation & Run
pip install -r requirements.txt
python app.py


Open in browser 🌐:

http://127.0.0.1:5000/

🧠 Model Information

🔹 Algorithm: Linear Regression

🔹 Input: Years of Experience

🔹 Output: Predicted Salary

⚠️ Disclaimer

This project is intended for learning and demonstration purposes only.
