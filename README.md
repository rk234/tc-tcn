# TC-TCN - TCN based Medium-Range Tropical Cyclone Track Forecasting

Experiments using multivariate TCN for tropical cyclone track forecasting. Model inputs included latitude, longitude, storm direction, wind speed, minimum atmospheric pressure, and engineered delta fields for specific variables over the past 72 hours of the storm's life. Forecasts include latitude and longitude over the next 24 hours. Model timestep was 3 hours.

## Results
![Mean Absolute Track Error vs. Forecast Timestep](https://github.com/rk234/tc-tcn/assets/106203063/672760db-7f6f-4b35-902f-c298c4185ebd)

## Storm Cases
Below are specific forecast cases for past tropical cyclones using the model with tracks visualized on a map using matplotlib and basemap. 

Blue Track - Model Forecast

Green Track - Ground Truth Storm Track

Orange Track - Past Tropical Cyclone positions used as model inputs

![case1](https://github.com/rk234/tc-tcn/assets/106203063/36c1d26e-c172-4d4c-99c3-c6ef3215a3aa)

![case2](https://github.com/rk234/tc-tcn/assets/106203063/3ca44797-8fe2-4d62-9539-5ccde7e7bab6)

![case3](https://github.com/rk234/tc-tcn/assets/106203063/905eb125-9b72-41aa-a8a2-1fbb6fca2cc7)

![case4](https://github.com/rk234/tc-tcn/assets/106203063/a836165a-2dd3-44a9-a77d-4a910be88661)

![case5](https://github.com/rk234/tc-tcn/assets/106203063/bb2bc7a0-06cb-4d9a-8a57-177e1f81652e)
