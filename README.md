# House Price Prediction

A machine learning project to predict house prices in Bengaluru using regression models.

## 📊 Project Overview

This project analyzes the Bengaluru housing dataset to build a predictive model for house prices based on features like location, square footage, number of bedrooms, and bathrooms.

## 🔧 Technologies Used

- **Python** - Core programming language
- **Pandas & NumPy** - Data manipulation and analysis
- **Scikit-learn** - Machine learning models
- **Matplotlib & Seaborn** - Data visualization
- **Google Colab** - Development environment

## 📁 Dataset

- **Source:** Bengaluru House Price Data
- **Records:** 13,320 properties
- **Features:** Location, size, total sqft, bath, balcony, price

## 🛠️ Data Preprocessing

- Handled missing values and null entries
- Standardized 1,300+ location entries
- Removed statistical outliers using IQR method
- Feature engineering for price per sqft

## 🤖 Models Implemented

| Model | Description |
|-------|-------------|
| Linear Regression | Baseline model |
| Lasso Regression | L1 regularization |
| Decision Tree | Non-linear approach |

## 📈 Results

- **Best Model:** Linear Regression
- **Accuracy:** 81.8%
- **Validation:** K-fold cross-validation (k=5)
- **Optimization:** GridSearchCV for hyperparameter tuning

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/harshgujarati/house-price-prediction.git
cd house-price-prediction
```

2. Install dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3. Run the notebook
```bash
jupyter notebook house_price_prediction.ipynb
```

## 📂 Project Structure

```
├── house_price_prediction.ipynb    # Main notebook with analysis
├── Bengaluru_House_Data.csv        # Dataset
└── README.md                       # Project documentation
```

## 📊 Key Insights

- Location is the strongest predictor of house prices
- Price per sqft varies significantly across neighborhoods
- 2-3 BHK apartments dominate the market
- Outlier removal improved model accuracy by ~5%

## 👤 Author

**Harsh Gujarati**
- GitHub: [@harshgujarati](https://github.com/harshgujarati)
- LinkedIn: [harshgujarati](https://linkedin.com/in/harshgujarati)
