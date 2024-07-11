# Early Warning Extreme Weather Prediction With Windowing Method

## Background
Sudden increases in temperature can have severe health impacts, such as heat stroke. European society is inadequately prepared for the escalation of extreme weather events. To address this critical issue, our project focuses on predicting extreme temperature occurrences. This early warning system aims to facilitate timely preventive measures.

## Solution
Developing an Early Warning Prediction Model for Extreme Temperatures

## Goal
To provide actionable information for communities to prepare effectively against extreme temperature events.

## Insights
Weather is said to be extreme if rainfall intensity, wind speed, atmospheric pressure, and dew point temperature have averages that are higher than normal limits.
Factors that can cause extreme weather:
- **Atmospheric pressure**: Above 2.2 atm
- **Rainfall**: Exceeding 3 mm
- **Wind speed**: Greater than 47 km/h
- **Wind direction**: Predominantly from the southwest
- **Dew point temperature**: Exceeding 1°C

## Windowing Prediction
Windowing prediction utilizes time series data techniques to forecast future values based on historical data features.

![Windowing Prediction](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/0027dc8e-ab4a-457e-a5e3-29d193b1a6ef)

## Top Features for Prediction
![Top Features](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/b85862a8-32b2-4df2-890b-9798382de4b0)

## Modeling and Evaluation
- **Data Split**: The dataset is split into 70% for training (train) and 30% for testing (test).
- **Methods**: We evaluate various methods including Logistic Regression, Decision Trees, Random Forest, XGBoost, and Gradient Boosting.
- **Evaluation**: Performance is assessed using a confusion matrix, emphasizing recall to gauge the model's effectiveness in detecting extreme temperature events.

### Recall Model Comparison
Gradient Boosting demonstrates superior recall, especially notable on Day 3.
![Recall Model Comparison](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/65a4a074-aee6-462b-a46e-09ae372e8a54)

### Matrix Evaluation
![Matrix Evaluation](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/d161476c-3e4a-4684-bf87-df8a258276f5)

## Recommendations
- **Public Awareness**: Educate communities about the health risks associated with extreme temperatures, such as heat strokes.
- **Early Warnings**: Implement a system for forecasting extreme temperature probabilities over the next 3 days to enable proactive community readiness.

## Dashboard
Access the interactive dashboard [here](https://lookerstudio.google.com/reporting/cbd224e4-21eb-4c28-9dd8-420e2e06c917).

![Dashboard 1](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/32ca5243-dae4-4778-8775-afff8519287f)
![Dashboard 2](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/cdddb8f7-83e5-4882-96fe-773ff6633fc8)
![Dashboard 3](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/8a4e333a-e9a9-45cc-85d2-08fdd1f027f9)
![Dashboard 4](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/b25deb1f-02d8-4a4b-959e-ad5b2c3d6f32)
