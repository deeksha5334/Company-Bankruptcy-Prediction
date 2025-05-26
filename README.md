# Company-Bankruptcy-Prediction

A web application that predicts whether a company might go bankrupt based on financial data.

## What it does

Enter a company's financial information and get a prediction about bankruptcy risk.

## How to run

1. Clone this repository
2. Install Python packages:
   ```
   pip install flask pandas numpy scikit-learn joblib
   ```
3. Run the app:
   ```
   python app.py
   ```
4. Open http://localhost:5000 in your browser

## Files

- `app.py` - Main Flask application
- `bankruptcy_model.pkl` - Trained machine learning model
- `scaler.pkl` - Data preprocessing tool
- `templates/` - HTML files
- `static/` - CSS and JavaScript files

## Usage

1. Fill in the financial data form
2. Click "Predict"
3. See if the company is at risk of bankruptcy

## Built with

- Python
- Flask
- scikit-learn
- HTML/CSS
