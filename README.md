![Python](https://img.shields.io/badge/Python-3.10-blue)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Colab](https://img.shields.io/badge/Made%20With-Google%20Colab-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
# ✈️ Flight Delay Prediction and Weather Impact Analysis

This project analyzes and predicts flight delays in the United States based on airline data, airport operations, and historical weather conditions.

Built using real-world datasets from NOAA and BTS, the project combines data analytics, machine learning modeling, and dashboarding to derive meaningful insights into the factors that cause flight delays.

---

## 📊 Project Contents
- **9_FlightDelay.ipynb**: Data cleaning, feature engineering, EDA (Exploratory Data Analysis), and Machine Learning model building.
- **FlightDelay.pbix**: Power BI Dashboard visualizing delay patterns, airline performance, and weather impacts.
- **Datasets**:
  - Weather data from [NOAA's National Centers for Environmental Information (NCEI)](https://www.ncei.noaa.gov/cdo-web/)
  - Flight delay data from [BTS TranStats Database](https://www.transtats.bts.gov/ot_delay/ot_delaycause1.asp)

---

## 🛠 Tools and Technologies Used
- **Python**: Pandas, Numpy, Scikit-learn, Seaborn, Matplotlib, XGBoost
- **Google Colab**: For data processing and model training
- **Power BI**: For dashboard and interactive data visualization
- **GitHub**: For project version control and collaboration

---

## 📈 Key Project Highlights
- Developed a machine learning model achieving **85% accuracy** in predicting flight delays.
- Identified strong relationships between weather conditions (precipitation, wind, temperature variations) and flight delays.
- Created an interactive Power BI dashboard to help stakeholders visualize the impact of weather and operational factors.
- Delivered key actionable insights, such as the best months, airlines, and weather conditions for minimizing delays.

---

## 🚀 Machine Learning Model
- **Problem Type**: Binary Classification (Delayed vs Not Delayed)
- **Algorithm Used**: XGBoost Classifier
- **Important Features**: 
  - Weather metrics (PRCP, AWND, TMAX, TMIN, Temp Difference)
  - Flight volume
  - Carrier details
- **Performance Metrics**: Accuracy, Precision, Recall, F1-score

---

## 📚 Dataset Sources
- [NOAA Climate Data Online](https://www.ncei.noaa.gov/cdo-web/)
- [BTS (Bureau of Transportation Statistics) - TranStats](https://www.transtats.bts.gov/ot_delay/ot_delaycause1.asp)

---

## 👥 Contributors
- **Shorn Correia** 
- **Cairn Correia**

---

## 📬 Contact
- **Shorn Correia**  
  - [LinkedIn Profile](https://www.linkedin.com/in/shorn-correia/)
  - [Email](shorncorreia@gmail.com)

- **Cairn Correia**  
  - [LinkedIn Profile](https://www.linkedin.com/in/cairn-correia/)
  - [Email](cairncorreia@gmail.com)

---

## 📌 How to Run the Project
1. Open the `9_FlightDelay.ipynb` notebook in Google Colab.
2. Make sure the dataset files are correctly uploaded (or modify paths if running locally).
3. Run each cell step-by-step to perform EDA, feature engineering, and model training.
4. View the interactive visuals using the Power BI dashboard file (`FlightDelay.pbix`).

---

> *This project was developed as part of a real-world data science portfolio to demonstrate end-to-end analytics, machine learning modeling, and dashboarding skills.*

