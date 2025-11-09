🚘 **Car Price Predictor**


📘 **Project Overview**

Car Price Predictor is a Flask-based web application that predicts the price of a used car based on user-selected features such as the company, model name, manufacturing year, fuel type, and driven kilometers.

It uses a cleaned car dataset and can be extended with a machine learning model for accurate price estimation. The app also provides a simple, intuitive interface to explore car data and understand pricing trends.

🧾 **Dataset Description**

The dataset used in this project is Cleaned_Car_Proper_Columns.csv, containing the following columns:

Column Name	Description
Car_Name	The name/model of the car
Company	Manufacturer or brand of the car
Year	Year of manufacture
Price	Selling price of the used car
Kms_Driven	Distance driven (in kilometers)
Fuel_Type	Type of fuel (Petrol, Diesel, CNG, etc.)

⚙️ **Technologies Used**

Python – Core programming language

Flask – Web framework for backend development

Pandas – Data manipulation and analysis

HTML + CSS (Jinja2 Templates) – Frontend structure and styling

Linear Regression – For ML-based price prediction

📁 **Project Structure**
Car-Price-Predictor/
│
├── app.py                         # Flask application
├── Cleaned_Car_Proper_Columns.csv  # Cleaned car dataset
├── model.pkl                       # (Optional) Trained ML model
└── templates/
    └── index.html                  # HTML frontend

💡 **Features**

1. Interactive web form to input car details:

Company

Model name

Manufacturing year

Fuel type

Driven kilometers

2. Dynamic dropdowns populated from dataset.

3. Can easily integrate a trained ML model for price prediction.

4. Clean and modular Flask structure — simple to extend and maintain.

🌱 **Future Enhancements**

Integrate a machine learning model for real-time price prediction.

Add data visualizations (e.g., average price per brand/year).

Improve UI with Bootstrap or Tailwind CSS.

Add a database (like SQLite) for storing predictions.
