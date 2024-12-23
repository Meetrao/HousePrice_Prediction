# HousePrice_Prediction

This repository contains a machine learning project aimed at predicting house prices based on various features such as square footage, number of bedrooms, bathrooms, lot size, and neighborhood quality. The project demonstrates the application of regression techniques to predict continuous target variables.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project was developed during a **6-day Machine Learning Workshop**, where the primary focus was on building predictive models using Python. The project showcases the application of linear regression to predict house prices and is designed to reinforce key concepts of supervised learning.

### Objectives
- Understand and preprocess housing data.
- Perform exploratory data analysis (EDA) and visualization.
- Train and evaluate a linear regression model.
- Predict house prices based on new input data.

## Dataset

The dataset consists of 1,000 samples with the following columns:
- `Square_Footage`: Total area of the house in square feet.
- `Num_Bedrooms`: Number of bedrooms.
- `Num_Bathrooms`: Number of bathrooms.
- `Year_Built`: Year the house was built.
- `Lot_Size`: Size of the lot in acres.
- `Garage_Size`: Number of garage spaces.
- `Neighborhood_Quality`: Quality rating of the neighborhood (scale: 1-10).
- `House_Price`: Price of the house (target variable).

### Sample Data
| Square_Footage | Num_Bedrooms | Num_Bathrooms | Year_Built | Lot_Size | Garage_Size | Neighborhood_Quality | House_Price   |
|----------------|--------------|---------------|------------|----------|-------------|-----------------------|--------------|
| 1360           | 2            | 1             | 1981       | 0.60     | 0           | 5                     | 262382.85    |
| 4272           | 3            | 3             | 2016       | 4.75     | 1           | 6                     | 985260.85    |

## Technologies Used

- **Python**
- **Jupyter Notebook**
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib/Seaborn
  - Scikit-learn

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git

	2.	Navigate to the project directory:

cd house-price-prediction


	3.	Install the required dependencies:

pip install -r requirements.txt


	4.	Launch Jupyter Notebook:

jupyter notebook


	5.	Open the HousePrice.ipynb file to explore the project.

Usage
	1.	Load the dataset (house_price_regression_dataset.csv).
	2.	Preprocess and explore the data using the provided notebook.
	3.	Train the regression model and evaluate its performance.
	4.	Use the trained model to make predictions on new data.

Project Structure

house-price-prediction/
│
├── HousePrice.ipynb          # Jupyter Notebook with the project code
├── house_price_regression_dataset.csv  # Dataset
├── README.md                 # Project README file
└── requirements.txt          # List of dependencies

Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Let me know if there's anything else you'd like to add or modify!
