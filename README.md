# 🌧️ Rainfall Prediction Classifier

This project is a machine learning-based classifier that predicts whether it will rain tomorrow, using historical weather data. It applies models such as **Logistic Regression** and **Random Forest Classifier**, performing **EDA**, **feature engineering**, and **model evaluation** to build an accurate prediction system.

---

##  Project Highlights

-  **Exploratory Data Analysis (EDA)**: Visualizations & insights on weather trends.
-  **Data Preprocessing**: Handling missing values, encoding categorical variables.
-  **Machine Learning Models**: Logistic Regression, Random Forest Classifier.
-  **Evaluation Metrics**: Accuracy, Confusion Matrix, and True Positive Rate.
-  **Best Performing Model**: Random Forest Classifier with higher TPR and accuracy.

---

## 📁 Dataset

- **Source**: [Australian Rainfall Dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)
- **Attributes**: Temperature, humidity, wind direction/speed, evaporation, etc.
- **Target**: `RainTomorrow` – Yes or No

---

##  Tech Stack

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Exploratory Data Analysis (EDA)

- Correlation matrix to identify key predictors
- Distribution plots of rainfall, temperature, and humidity
- Missing value heatmaps and feature importance graphs

---

##  Model Building

| Model               | Accuracy | True Positive Rate |
|---------------------|----------|--------------------|
| Logistic Regression | 84%      | 51%                |
| Random Forest       | 83%      | 50%                |

👉 *Random Forest performed better due to its robustness with non-linear relationships and higher ability to handle noise.*

---

##  Key Takeaways

- **Feature importance analysis** showed that some meteorological variables, such as **Humidity at 9 AM**, **Evaporation**, and **Wind Gust Direction**, were less effective predictors.
- **Logistic Regression** slightly outperformed **Random Forest** in accuracy (**84% vs. 83%**), but both models struggled with recall for rainy days.
- **True Positive Rate (TPR)** for predicting rain is moderate (**~51%**), indicating that the model misses some actual rainy days.
- Real-world application in **agriculture**, **weather reporting**, and **disaster prevention systems**.

---

##  Future Improvements

- Hyperparameter tuning for improved performance
- Feature selection using SHAP or recursive elimination
- Deploying using Flask/Streamlit for real-time predictions

---

## Contact

**Navya Kannan**  
navyakannanvadakoote@gmail.com  
www.linkedin.com/in/navya-kannan-vadakoote

---

> ⭐ *If you like this project, give it a star!*
