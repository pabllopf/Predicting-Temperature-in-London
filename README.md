# Predicting-Temperature-in-London
Perform a machine learning experiment to find the best model that predicts the temperature in London!

# Description:
As the climate changes around the world, the ability to predict changing weather is becoming more and more important.

In this project you will work on predicting the mean temperature in London. You will import, preprocess, and explore historical weather data and automate the training and evaluation of multiple machine learning models. This will be setup in an automated workflow using functions, utilizing methods from sklearn and MLflow.


# Project Instructions
Use machine learning to predict the mean temperature in London, England, logging your root mean squared error (RMSE) metrics using mlflow.

Build a model to predict "mean_temp" with a RMSE of 3 or less.
Use MLflow to log any models you train, their hyperparameters, and respective RMSE scores (ensuring you include "rmse" as part of the metric name).
Search all of your mlflow runs and store the results as a variable called experiment_results.

![image](https://github.com/user-attachments/assets/1e3c655d-fbac-4223-82b9-586bc8c89418)


As the climate changes, predicting the weather becomes ever more important for businesses. You have been asked to support on a machine learning project with the aim of building a pipeline to predict the climate in London, England. Specifically, the model should predict mean temperature in degrees Celsius (°C).

Since the weather depends on a lot of different factors, you will want to run a lot of experiments to determine what the best approach is to predict the weather. In this project, you will run experiments for different regression models predicting the mean temperature, using a combination of `sklearn` and `mlflow`.

You will be working with data stored in `london_weather.csv`, which contains the following columns:
- **date** - recorded date of measurement - (**int**)
- **cloud_cover** - cloud cover measurement in oktas - (**float**)
- **sunshine** - sunshine measurement in hours (hrs) - (**float**)
- **global_radiation** - irradiance measurement in Watt per square meter (W/m2) - (**float**)
- **max_temp** - maximum temperature recorded in degrees Celsius (°C) - (**float**)
- **mean_temp** - **target** mean temperature in degrees Celsius (°C) - (**float**)
- **min_temp** - minimum temperature recorded in degrees Celsius (°C) - (**float**)
- **precipitation** - precipitation measurement in millimeters (mm) - (**float**)
- **pressure** - pressure measurement in Pascals (Pa) - (**float**)
- **snow_depth** - snow depth measurement in centimeters (cm) - (**float**)
