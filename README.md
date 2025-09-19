# Divyanshi-Saxena_RideWise-Bike-Prediction

ℙℝ𝕆𝕁𝔼ℂ𝕋 𝕆𝕍𝔼ℝ𝕍𝕀𝔼𝕎
-----------------------

RideWise is a machine learning project that predicts bike rental demand based on time, weather, and event-related factors. Using historical bike-sharing data, the project applies data preprocessing, feature engineering, regression models, and deployment techniques to make accurate forecasts. The aim is to optimize bike availability, reduce waiting times, and support sustainable urban mobility.

ℝ𝔼ℙ𝕆𝕊𝕀𝕋𝕆ℝ𝕐 ℂ𝕆ℕ𝕋𝔼ℕ𝕋𝕊
--------------------------

RIDEWISE_DIVYANSHI_SAXENA.ipynb → Main Colab notebook (all steps from preprocessing to deployment).

day.csv → Original daily dataset.

hour.csv → Original hourly dataset.

day_cleaned.csv → Cleaned daily dataset after preprocessing.

hour_cleaned.csv → Cleaned hourly dataset after preprocessing.

README.md → Project description and usage instructions.

Other files like the saved pipeline (.pkl) and Flask/Streamlit app scripts can be generated directly by running the notebook in Colab.

ℍ𝕆𝕎 𝕋𝕆 𝕌𝕊𝔼
---------------

Clone this repository or download the files.

Open RIDEWISE_DIVYANSHI_SAXENA.ipynb in Google Colab.

Upload the provided datasets (day.csv and hour.csv).

Run the notebook step by step:

Data cleaning & preprocessing

Feature engineering

Model training & evaluation

Hyperparameter tuning (GridSearchCV)

Model saving & deployment (Flask/Streamlit)

Cleaned datasets (day_cleaned.csv, hour_cleaned.csv) are also included for quick reference.

ℝ𝔼𝕊𝕌𝕃𝕋𝕊 𝕊𝕌𝕄𝕄𝔸ℝ𝕐
----------------------

Best model: Tuned Random Forest Regressor

R² Score: ~0.95 (excellent prediction accuracy)

Most important features: Hour, Temperature, Humidity, Rush Hour, Working Day



Ensure all required libraries are installed (the notebook includes installation commands if needed).
