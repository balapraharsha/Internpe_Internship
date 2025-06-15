# 🏏 IPL Score Predictor using Machine Learning

This project was developed as part of my **InternPe Internship**, focusing on predicting the **final score of a T20 innings** in an IPL match using machine learning models.

---

## 📌 Project Overview

The aim of this project is to estimate the total score a team might reach by the end of their innings based on the current match conditions using regression models.

---

## 📂 Dataset Used

The dataset includes real match data with the following key features:

- `venue`: Stadium where the match is played  
- `batting_team`: Team currently batting  
- `bowling_team`: Team currently bowling  
- `current_score`: Runs scored so far  
- `wickets`: Total wickets fallen  
- `overs`, `balls`: Progress of innings  
- `runs_last_5`: Runs scored in the last 5 overs  
- `predicted_score`: Target variable — final innings score

---

## 🛠️ Tech Stack

- **Python 🐍**  
- **Pandas & NumPy** for data manipulation  
- **Scikit-learn** for model building  
- **Matplotlib & Seaborn** for data visualization  
- **Jupyter Notebook** (Colab)

---

## 🧼 Data Preprocessing

- Removed irrelevant features (`mid`, `date`, `batsman`, `bowler`, etc.)
- Filtered only **1st innings** data for consistency
- Handled categorical features with **One-Hot Encoding**
- Engineered `runs_last_5` as a recent scoring trend indicator
- Cleaned inconsistent entries and standardized values

---

## 🤖 Models Trained

- **Linear Regression**
- **Random Forest Regressor**

---

## 📊 Model Performance

### 🔹 Linear Regression
- **R² Score**: 0.87  
- **MAE**: 5.10  
- **RMSE**: 9.36  

### 🔹 Random Forest Regressor ✅
- **R² Score**: 0.92  
- **MAE**: 4.02  
- **RMSE**: 8.20  

---

## 📌 Sample Prediction

- **Predicted Score**: 🏏 186  
- **Actual Score**: 🏏 190  

---

## 🎯 Conclusion

This project showcases how **machine learning** can help in **real-time sports analytics**, such as score prediction.  
The **Random Forest** model performed better due to its ability to model non-linear patterns and feature interactions.

---

## 🔮 Future Improvements

- ✅ Deploy using **Streamlit** or **Flask**  
- ✅ Integrate **live match API** for real-time predictions  
- ✅ Try **advanced models** like XGBoost or LightGBM  
- ✅ Include more match features like player stats, strike rates, and economy

---

## 📁 Project Structure

IPL_Score_Prediction/
├── ipl_score_predictor.ipynb       # Main notebook
├── ipl_colab.csv                   # Dataset
├── requirements.txt                # Dependencies
└── README.md                       # This file

---

## 🔖 Author

Developed by **Mannepalli Bala Praharsha**  
Made with ❤️ during my **InternPe Internship**  

📫 Connect on [LinkedIn](https://www.linkedin.com/in/mannepalli-bala-praharsha)

---

## 🏷️ Tags

`#InternPe` `#Internship` `#MachineLearning` `#DataScience` `#Python` `#ScikitLearn` `#CricketAnalytics` `#MLProject` `#SportsTech` `#IPLPrediction`


