# Early Warning Extreme Weather Prediction With Windowing Method

## Background
Sudden increases in temperature can cause severe health impacts, such as heat stroke. European society is not prepared for the rise in extreme weather. To address this issue, we propose a solution that involves predicting extreme temperature events. This early warning system is crucial for implementing the necessary precautions.

## Solution
Creating an Early Warning Prediction Model for Extreme Temperature

## Goal
To provide information so that people can prepare for extreme temperatures.

## Insights
Weather is considered extreme if the following factors have averages that exceed normal limits:
- **Atmospheric pressure**: Above 2.2 atm
- **Rainfall**: Above 3 mm
- **Wind speed**: Above 47 km/h
- **Wind direction**: Southwest
- **Dew point temperature**: Above 1°C

## Windowing Prediction
Windowing prediction is a time series data predictive technique to predict future target values using past features.

![Windowing Prediction](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/0027dc8e-ab4a-457e-a5e3-29d193b1a6ef)

## Top Feature for Prediction
![Top Feature](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/b85862a8-32b2-4df2-890b-9798382de4b0)

## Modeling and Evaluation
- **Data Split**: The dataset is divided with a ratio of 80% for training data (train) and 20% for test data (test).
- **Experimentation**: Methods such as Logistic Regression, Decision Tree, Random Forest, XGBoost, and Gradient Boosting are experimented with.
- **Evaluation**: Evaluation is done using a confusion matrix. Recall is important because it measures how many extreme temperature events the model successfully detects. If the model often fails to detect extreme temperatures that actually occur, it will be fatal.

### Recall Model Comparison
Gradient Boosting has a superior recall value compared to other models. The recall testing value on Day 3 has the highest value.

![Recall Model Comparison](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/65a4a074-aee6-462b-a46e-09ae372e8a54)

### Matrix Evaluation
![Matrix Evaluation](https://github.com/code1wan/extreme-weather-prediction/assets/133578726/d161476c-3e4a-4684-bf87-df8a258276f5)

## Recommendation
- **Socialization**: Educate the public about the effects of extreme temperatures that are at risk of causing heat stroke and other health issues.
- **Early Warnings**: Deliver early warnings of the probability of extreme temperatures for the next 3 days, hoping that the community will be ready to face extreme temperatures.

## Dashboard
