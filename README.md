#WORK IN PROGRESS
# HousePricePrediction

A machine learning project to predict house prices based on various features such as area, bedrooms, bathrooms, and other amenities.

## Project Structure

- `data/`
  - `raw/`: Contains the original, uncleaned data (`Housing.csv`) and its description (`description.txt`).
  - `processed/`: Contains the cleaned and transformed data ready for modeling.
- `notebooks/`
  - `01_Data_Cleaning.ipynb`: Initial data exploration, handling missing values, and data cleaning.
  - `02_Feature_Engineering.ipynb`: Transforming variables, creating new features, and preparing data for models.
  - `03_Models.ipynb`: Training, evaluating, and comparing different machine learning models.
- `models/`: Directory to store trained machine learning models.

## Dataset

The dataset contains the following features:
- **price**: Price of the house (Target Variable)
- **area**: Area of the house
- **bedrooms**: Number of bedrooms
- **bathrooms**: Number of bathrooms
- **stories**: Number of stories
- **mainroad**: Whether the house is connected to the main road
- **guestroom**: Whether the house has a guest room
- **basement**: Whether the house has a basement
- **hotwaterheating**: Whether the house has a hot water heater
- **airconditioning**: Whether the house has air conditioning
- **parking**: Number of parking spaces
- **prefarea**: Whether the house is in a preferred area
- **furnishingstatus**: Furnishing status of the house

## Requirements

The project uses the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`
- `pathlib`

You can install the dependencies using:
```bash
pip install -r requirements.txt
```

## Getting Started

1. Clone this repository.
2. Install the required dependencies: `pip install -r requirements.txt`.
3. Open the Jupyter notebooks in the `notebooks/` directory sequentially to see the data processing and modeling steps.
