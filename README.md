# Car Price Prediction App

This project is a web-based application built using Flask that predicts the price of a car based on various input features. The application uses a machine learning model trained on a dataset of car prices to provide predictions.

## Features
- Web interface to input car details such as model, year, mileage, etc.
- Uses a pre-trained machine learning model to predict the price of a car.
- Simple and user-friendly interface built using HTML, CSS, and Flask.
- Deployed locally on your machine or can be hosted on a cloud service.

## Prerequisites
To run this project locally, ensure you have the following installed:

- Python 3.x
- Flask
- pandas
- scikit-learn
- numpy
- Jupyter (if you want to view the notebook)

You can install the required packages by running:

```bash
pip install Flask pandas scikit-learn numpy
```

## Project Structure
```bash
├── app.py                  # Main Flask application
├── model.pkl               # Trained machine learning model
├── templates/              # HTML files for the frontend
│   └── index.html          # Home page for the app
├── static/                 # Static assets like CSS and images
│   └── styles.css          # Styles for the web page
├── Car_price_predictor.ipynb # Jupyter notebook with the data analysis and model training
└── README.md               # Project description and setup
```

## How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/car-price-predictor.git
   cd car-price-predictor
   ```

2. **Train the Model (Optional):**
   
   If you want to retrain the model, open the `Car_price_predictor.ipynb` file in Jupyter and follow the steps to preprocess the data and train the model.

3. **Run the Flask App:**

   To run the app locally, execute:

   ```bash
   python app.py
   ```

4. **Access the App:**

   Open your web browser and navigate to:

   ```
   http://127.0.0.1:5000/
   ```

5. **Input Car Features:**

   Enter details such as the car make, model, year, mileage, and other features, and the app will predict the car's price based on the input.

## Model Training (Notebook)
The `Car_price_predictor.ipynb` notebook contains the full workflow for data cleaning, feature selection, and model training. The machine learning model is exported as a `.pkl` file and used by the Flask app for making predictions.

## Future Improvements
- Deploy the app on cloud platforms like Heroku or AWS.
- Enhance the UI to improve user experience.
- Add more features for better prediction accuracy.
