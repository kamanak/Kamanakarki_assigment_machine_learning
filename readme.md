# Solar Power Prediction Using Machine Learning

## Project Overview
This project aims to predict solar power generation using machine learning models. It includes two datasets and an accompanying Jupyter Notebook that demonstrates data preprocessing, model training, and making predictions.

## Project Structure

### Datasets:
- **Dataset (`Plant_2_Generation_Data.csv`)**: Contains historical data with features such as `DATE_TIME`,`PLANT_ID`,`SOURCE_KEY`,`DC_POWER`,`AC_POWER`,`DAILY_YIELD`,`TOTAL_YIELD`
- **Dataset (`Plant_2_Weather_Sensor_Data.csv`)**: A separate dataset consisting of `DATE_TIME`,`PLANT_ID`,`SOURCE_KEY`,`AMBIENT_TEMPERATURE`,`MODULE_TEMPERATURE`,`IRRADIATION`

### Jupyter Notebook (`solar_power_prediction.ipynb`):
- **Data Loading and Exploration**: Load the datasets and perform initial exploration.
- **Data Preprocessing**: Handle missing values, remove outliers, and clean the data.
- **Feature Engineering**: Engineer useful features for model training.
- **Model Selection and Hyperparameter Tuning**: Use `Random Forest Regressor` and tune the model using `RandomizedSearchCV`.
- **Prediction on Test Data**: Make predictions on unseen test data.
- **Model Evaluation**: Evaluate model performance using metrics like RMSE (Root Mean Square Error).

## Steps to Run the Project

1. **Clone the Repository**: Download or clone the repository containing the datasets and Jupyter Notebook.
   ```bash
   git clone <repository-link>
