# Disease Prediction Using Machine Learning

## Project Overview

This project uses Machine Learning to predict disease categories based on blood sample data. It includes data preprocessing, feature analysis, model training, evaluation, and an interactive web application.

The project uses a Multinomial Logistic Regression model to classify samples into five categories: Healthy, Diabetes, Anemia, Thalassemia, and Thrombocytopenia.

## Features

- Disease prediction using Machine Learning
- Blood sample data analysis
- Data preprocessing and feature analysis
- Logistic Regression classification
- Interactive prediction dashboard
- Data visualization and insights
- Model evaluation using performance metrics
- Class probability visualization

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Streamlit
- Plotly
- Joblib

## Project Structure

```text
disease-prediction/
├── assets/
├── models/
├── app.py
├── Blood_samples_dataset_balanced.csv
├── disease prediction .ipynb
├── requirements.txt
└── README.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/megamithra/disease-prediction.git
```

### 2. Navigate to the project folder

```bash
cd disease-prediction
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

The application will open in your web browser.

## Model

The project uses a Multinomial Logistic Regression model for disease classification.

## Visualizations

The `assets` folder contains:

- Class distribution
- Confusion matrix
- Correlation heatmap
- Feature distributions
- Feature importance
- ROC curves

## Disclaimer

This project is developed for educational and demonstration purposes only. It is not a substitute for professional medical diagnosis or clinical advice.

## Author

Megamithra