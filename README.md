# 💼 Employee Salary Prediction System

## 🔍 Overview
The Employee Salary Prediction System predicts an employee’s salary based on **years of experience** using **Machine Learning**.  
It leverages a **Linear Regression** model trained on historical data and provides predictions through a **Flask-based web application**.

## 🚀 Features
- Perform Exploratory Data Analysis (EDA) on salary data  
- Data preprocessing and feature selection  
- Train a Linear Regression model  
- Save and reuse the trained model using Pickle  
- Web-based prediction interface using Flask  
- Simple, clean, and beginner-friendly implementation  

## 🧠 Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, pickle  
- **Web Framework:** Flask  
- **Frontend:** HTML  

## 🏗️ Project Structure
<img width="1119" height="425" alt="image" src="https://github.com/user-attachments/assets/3ed3958a-402d-438f-b2a0-8a93a5f76510" />



## ⚙️ How It Works
1. User enters years of experience.  
2. Input is processed by the trained Linear Regression model.  
3. Model predicts the expected salary.  
4. Result is displayed on the web interface.  

## ▶️ Usage
1. Run the Flask application:

```bash
python app.py
http://127.0.0.1:5000/
Enter years of experience and click Predict Salary to view the predicted salary instantly.

📊 Example Prediction
Years of Experience	Predicted Salary
2.5	₹3,20,000
🧩 Future Enhancements

Add more features (education, role, location)

Improve UI using Bootstrap or similar frameworks

Deploy on Render / AWS / Heroku

Add model comparison & evaluation metrics

⚠️ Disclaimer

This project is intended for educational and demonstration purposes only.
Predicted salaries may not reflect real-world compensation standards.
