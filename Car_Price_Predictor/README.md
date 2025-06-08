# 🚗 Car Price Predictor using Machine Learning

This project is part of my **InternPe Internship** and focuses on predicting the price of used cars using machine learning models trained on real-world car listings data.

## 📌 Project Overview

The goal is to predict the **selling price of a car** based on its features like name, year, fuel type, kilometers driven, transmission, and ownership history. The dataset was scraped from Quikr and cleaned extensively for training.

## 📂 Dataset Used

The dataset contains the following features:

- `name`: Car model name
- `year`: Year of manufacturing
- `selling_price`: The actual price the car was sold for
- `km_driven`: Total kilometers driven
- `fuel_type`: Type of fuel (Petrol/Diesel/LPG/CNG)
- `transmission`: Manual or Automatic
- `owner`: Ownership details (First Owner, Second Owner, etc.)

## 🛠️ Tech Stack

- Python 🐍
- Pandas & NumPy for data manipulation
- Scikit-learn for model building
- Matplotlib & Seaborn for data visualization

## 🧼 Data Preprocessing

- Removed outliers and null entries
- Extracted brand names from car names
- Handled categorical variables via one-hot encoding
- Created new feature `car_age` to enhance prediction

## 🤖 Models Trained

Two regression models were trained and compared:

- **Linear Regression**
- **Random Forest Regressor**

## 📊 Results

**Linear Regression**
- R² Score  : 0.684
- MAE       : ₹86,440.87
- RMSE      : ₹131,624.73

**Random Forest Regressor**
- R² Score  : 0.705
- MAE       : ₹81,690.14
- RMSE      : ₹127,210.56

📌 **Sample Prediction**
```
Predicted Price: ₹204,665  
Actual Price   : ₹210,000  
```

## 🎯 Conclusion

This project demonstrated how machine learning can be used to predict used car prices effectively. The Random Forest model showed better performance compared to Linear Regression.

### 🔮 Future Improvements

- Deploy using Streamlit or Flask
- Experiment with XGBoost and LightGBM
- Use more car attributes like mileage, torque, engine size, etc.

## 📁 Project Structure

```
Diabetes_Prediction/
│
├── car_price_predictor.ipynb   # Main Python code
├── quikr_car.csv               # Dataset
├── requirements.txt            # Dependencies
└── README.md                   # Project README
```

## 🔖 Author

Developed by **Mannepalli Bala Praharsha** 
For queries, feel free to connect via [LinkedIn](https://www.linkedin.com/in/mannepalli-bala-praharsha).
Made with ❤️ during my [InternPe](https://internpe.in) internship.

## 📌 Tags

`#InternPe` `#Internship` `#MachineLearning` `#DataScience` `#Python` `#ScikitLearn` `#MLProject`

