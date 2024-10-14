
# House Price Prediction Using Machine Learning

## Description
This project aims to predict house prices based on a dataset from Ames, Iowa, using machine learning techniques. We applied models such as **Linear Regression** and **Random Forest** to estimate house sale prices using 79 features describing residential homes, including lot size, construction quality, and location.

## Dataset
The dataset used for this project comes from the [Kaggle House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). It contains detailed information on housing features and sale prices for homes in Ames, Iowa.

## Installation/Requirements
The following Python libraries are required to run this project:
```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
fpdf
```

You can install these dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd house-price-prediction
   ```
3. Run the main script to train the models and generate predictions:
   ```bash
   python house_price_prediction.py
   ```

## Results
The performance of the models is evaluated using RMSE (Root Mean Squared Error):
- **Linear Regression RMSE (Original Scale)**: 0.174
- **Random Forest RMSE (Original Scale)**: 0.168

The tuned Random Forest model provided the best performance on this dataset.

## License
This project is open source and available under the [MIT License](LICENSE).
