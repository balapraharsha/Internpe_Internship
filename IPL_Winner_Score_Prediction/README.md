🏏 IPL Score Predictor using Machine Learning

This project is part of my **InternPe Internship** and focuses on predicting the **final score of a T20 cricket innings** using machine learning models trained on ball-by-ball IPL match data.

📌 Project Overview  
The goal is to build a predictive model that estimates the total score of a team during an ongoing innings using features like current score, wickets, overs, and team dynamics. The dataset contains real IPL match data with detailed deliveries and match-level information.

📂 Dataset Used  
The dataset includes the following features:

- `venue`: Stadium where the match is played  
- `batting_team`, `bowling_team`: Teams involved  
- `current_score`: Runs scored till the current point  
- `wickets`: Wickets fallen till now  
- `overs`, `balls`: Current progress of the innings  
- `runs_last_5`: Runs scored in the last 5 overs  
- `predicted_score`: Target variable (final score at end of 20 overs)

🛠️ Tech Stack  
- Python 🐍  
- Pandas & NumPy for data manipulation  
- Scikit-learn for model building  
- Matplotlib & Seaborn for data visualization  
- Jupyter Notebook / Google Colab

🧼 Data Preprocessing  
- Dropped irrelevant features (e.g., player names, IDs)  
- Filtered dataset for first innings only (T20 format)  
- Encoded categorical variables (teams, venue) using One-Hot Encoding  
- Created feature `runs_last_5` for recent scoring trend  
- Standardized formats and cleaned missing/inconsistent entries

🤖 Models Trained  
Two regression models were trained and compared:

- **Linear Regression**  
- **Random Forest Regressor**

📊 Results  

**Linear Regression**
- R² Score: 0.87  
- MAE: 5.10  
- RMSE: 9.36  

**Random Forest Regressor**
- R² Score: 0.92 ✅  
- MAE: 4.02  
- RMSE: 8.20  

📌 Sample Prediction

- Predicted Score: 🏏 186  
- Actual Score   : 🏏 190  

🎯 Conclusion  
This project demonstrates how machine learning can be used to model and forecast sports performance. **Random Forest** showed better accuracy over Linear Regression due to its ability to handle non-linear patterns and feature interactions.

🔮 Future Improvements  
- Deploy as a web app using Streamlit or Flask  
- Integrate live match API for real-time predictions  
- Add features like run rate, batting average, or player-level stats  
- Compare more advanced ML models (e.g., XGBoost)

📁 Project Structure  
IPL_Score_Prediction/  
│  
├── ipl_score_predictor.ipynb     # Main notebook  
├── ipl_colab.csv                 # Dataset  
├── requirements.txt              # Dependencies  
└── README.md                     # This README file

🔖 Author  
Developed by **Mannepalli Bala Praharsha**  
For queries, feel free to connect via [LinkedIn](https://www.linkedin.com/in/mannepalli-bala-praharsha).

Made with ❤️ during my **InternPe** internship.

📌 Tags  
#InternPe #Internship #MachineLearning #DataScience #CricketAnalytics #Python #ScikitLearn #MLProject #SportsTech #IPLPrediction #AI #MLModels #Regression
