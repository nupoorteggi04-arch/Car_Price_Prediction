# Car_Price_Prediction
A machine learning project that predicts the selling price of used cars using Random Forest Regression based on various vehicle specifications.

# Features
- 🚘 Predicts used car prices accurately.
- 📊 Performs data preprocessing and feature engineering.
- 🤖 Uses Random Forest Regression for prediction.
- 📈 Evaluates model performance using regression metrics.
- 📚 Built completely in Jupyter Notebook.

# Technology Stack
- Programming Language: Python
- IDE: Jupyter Notebook
- Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
# Dataset
| Feature | Description |
|---------|-------------|
| Car ID | Unique identifier |
| Brand | Car manufacturer |
| Model | Car model |
| Year | Manufacturing year |
| Engine Size | Engine capacity |
| Fuel Type | Petrol/Diesel/Electric |
| Transmission | Manual/Automatic |
| Mileage | Distance travelled |
| Condition | Vehicle condition |
| Price | Selling Price (Target Variable) |

# Machine Learning Overflow
Load Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Handle Missing Values
        │
        ▼
Encode Categorical Variables
        │
        ▼
Train-Test Split
        │
        ▼
Random Forest Regressor
        │
        ▼
Model Evaluation
        │
        ▼
Price Prediction

# Project Structure
Car-Price-Prediction/
│
├── data/
│   └── car_price_prediction_.csv
│
├── notebooks/
│   └── Car_Price_Prediction.ipynb
│
├── images/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore

# Installation
Clone the repository

```bash
git clone https://github.com/nupoorteggi04-arch/Car-Price-Prediction.git
```

Move into the project folder

```bash
cd Car-Price-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Car_Price_Prediction.ipynb
```

and run all cells.
# Results
The Random Forest Regression model predicts used car prices using:

- Brand
- Model
- Year
- Engine Size
- Fuel Type
- Transmission
- Mileage
- Vehicle Condition

The notebook includes model training, evaluation, and price prediction.

