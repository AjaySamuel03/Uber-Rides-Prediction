# Uber-Rides-Prediction
A Machine Learning Flask web application that predicts the number of weekly Uber rides based on price, population, income, and parking data. Includes ML model training, dataset, model deployment with Flask, and a modern UI with custom CSS.
This project is a Machine Learning–powered Flask web application that predicts the number of weekly Uber rides in a city based on key economic and demographic factors, including weekly price, population, income, and parking cost.
The project demonstrates the end-to-end workflow of data preprocessing → model training → pickle serialisation → Flask deployment → UI development.
📸 Screenshots
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/f9dd59a6-5f72-465c-99dc-289784a53cb2" />
📊 Features:
1. Predicts number of weekly Uber rides
2. Clean & modern UI (custom CSS with gradients & glassmorphism)
3 .Built using Flask
4 .Machine Learning model using Linear Regression
5. Real-world-like dataset (taxi.csv)
6. Easy to deploy on Render, Railway, or Heroku
7.Fully customizable front-end

📁 Dataset: taxi.csv
The dataset contains the following columns:
| Feature                     | Description            |
| --------------------------- | ---------------------- |
| `Price per week`            | Cost of rides per week |
| `Population`                | City population        |
| `Monthly income`            | Average monthly income |
| `Average parking per month` | Parking cost           |
| `Number of weekly rides`    | **Target variable**    |

🤖 Machine Learning Model
Algorithm: Linear Regression
Libraries used:
pandas
numpy
scikit-learn
pickle
The model was trained in the Jupyter Notebook file:
MLmodel.ipynb
The trained model is saved as:
model.pkl
This file is loaded inside Flask for prediction.

🛠️ Tech Stack

Backend:

Python
Flask
Scikit-Learn
NumPy
Pickle

Frontend

HTML5
CSS3
Custom gradients & animations
Responsive design

🧩 Project Structure:
Uber_Ride_Predictor/
│── static/
│    └── style.css
│
│── templates/
│    └── index.html
│
│── MLmodel.ipynb
│── model.pkl
│── taxi.csv
│── app.py
│── README.md
│── .gitignore

🧮 Prediction Formula (Model Insight):
Your trained linear regression model finds a relationship:
Weekly Uber Rides = β0 + β1*(Price) + β2*(Population) + β3*(Income) + β4*(Parking)

The model predicts weekly rides based on the inputs from the UI.

📄 License
This project is open-source under the MIT License.

🙌 Author
👤 Ajay Samuel
MBA – Business Analytics
Illinois Tech – Stuart School of Business
leetcode: https://leetcode.com/u/Ajay_Samuel/
LinkedIn: www.linkedin.com/in/ajaysamuel03
