# Disease Prediction Using Machine Learning

## Project Overview
This project uses Machine Learning techniques to predict diseases based on blood sample data. It includes data preprocessing, model training, evaluation, and a web-based application for disease prediction.

## Features
- Disease prediction using Machine Learning
- Data preprocessing and feature analysis
- Logistic Regression model
- Data visualization and analysis
- Model evaluation using performance metrics
- Interactive web application using Flask

## Technologies Used
- Python
- Machine Learning
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Flask

## Project Structure
```text
disease-prediction/
│
├── assets/
│   ├── class_distribution.png
│   ├── confusion_matrix.png
│   ├── correlation_heatmap.png
│   ├── feature_distributions.png
│   ├── feature_importance.png
│   └── roc_curves.png
│
├── models/
│   ├── feature_names.pkl
│   ├── feature_stats.json
│   ├── label_encoder.pkl
│   ├── logistic_regression_model.pkl
│   ├── metrics.json
│   └── scaler.pkl
│
├── app.py
├── Blood_samples_dataset_balanced.csv
├── disease prediction .ipynb
├── requirements.txt
└── README.md
```

## Installation and Setup

1. Clone the repository:
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Navigate to the project folder:
```bash
cd "disease prediction"
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

## Model
The project uses Logistic Regression for disease prediction.

## Visualizations
The `assets` folder contains:
- Class distribution
- Confusion matrix
- Correlation heatmap
- Feature distributions
- Feature importance
- ROC curves

## Author
Megamithra

## Disclaimer
This project is developed for educational purposes and should not be used as a substitute for professional medical diagnosis.