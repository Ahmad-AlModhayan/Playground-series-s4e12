# Insurance Premium Prediction - Kaggle Playground Series S4E12

## Project Overview
This project is part of the Kaggle Playground Series Season 4, Episode 12, focusing on predicting insurance premium amounts using machine learning techniques.

## Project Structure
```
.
├── data/                    # Data directory
│   ├── train.csv           # Training dataset
│   └── test.csv            # Test dataset
├── Insurance_Premium_Prediction.ipynb  # Main notebook with all code
├── requirements.txt        # Python dependencies
└── README.md              # Project documentation

```

## Features
The dataset includes various features related to insurance policies:
- Demographic information (Age, Gender, Marital Status)
- Financial indicators (Annual Income, Credit Score)
- Health-related features (Health Score, Smoking Status)
- Policy details (Policy Type, Insurance Duration)
- And more...

├── data/               # Data files
├── Kaggle_Competition.ipynb # Data files
├── requirements.txt    # Python dependencies
├── submission.csv      # Submission File
└── README.md           # This file
```
 
## Setup

## Approach
1. **Data Preprocessing**
   - Handle missing values
   - Feature scaling
   - Categorical encoding


2. **Feature Engineering**
   - Date feature extraction
   - Interaction features
   - Risk-based features

3. **Modeling**
   - Ensemble of XGBoost and LightGBM
   - K-fold cross-validation
   - Log transformation of target variable

## Setup and Installation
1. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # or
   .\venv\Scripts\activate  # Windows
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   - Open Jupyter Notebook
   - Navigate to Insurance_Premium_Prediction.ipynb
   - Run all cells

## Model Performance
- Uses RMSLE (Root Mean Squared Logarithmic Error) as evaluation metric
- Implements k-fold cross-validation for robust evaluation
- Ensemble approach combines predictions from multiple models

## Dependencies
- Python 3.11+
- pandas
- numpy
- scikit-learn
- xgboost
- lightgbm
- matplotlib
- seaborn
- optuna
