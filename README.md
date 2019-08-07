# Bikes Prediction at any given station
The project is about predicting the city bicycles availability at the docking stations at any given hour. 

Three "csv" files are provided, the job is to do ETL, data understanding and apply machine learning model to predict number of bikes at any given station at any given time in any given city. 

The goal of the project is to help bike-loading company in the city by predictiing bikes change in next hour so that loading can be performed efficiently. 

The motive of the bike-loading compnay is to keep bikes available for customers to take bike and also free spots available to return bikes.

With this model the bike-company can get information about the bikes and free spots available at any given station.

This is the map of the city, with red balls indicating stations in the given city. By clicking on the red balls the bike availability can be seen.
![Map_with_stations](https://user-images.githubusercontent.com/44444144/61697319-ea267300-ad2e-11e9-850f-16ac0fb3e17e.png)

## Notebooks

[EDA and data understanding](https://github.com/ShashiSingam/Bike-Share-Project/blob/master/Final_EDA_Merging_revisited.ipynb): Exploratory data analysis, understanding of data, merging of data

[Modeling for one city](https://github.com/ShashiSingam/Bike-Share-Project/blob/master/HOUR_Final_model_bikeshare_regression.ipynb): develop machine learning algorithms to predict labels from features; use automated genetic search tools to search for best model.

[Modeling for all cities](https://github.com/ShashiSingam/Bike-Share-Project/blob/master/Loop_for_a_city.ipynb): After selecting the best model to fit for one station by perfroming hyperparameter tuning then model is applied on all the cities by looping over the cities.

## Feature Importances
![Feature_importance_model](https://user-images.githubusercontent.com/44444144/62619289-4df39300-b90e-11e9-8c31-b769cf60f306.png)
![feature_importance_SHAP](https://user-images.githubusercontent.com/44444144/62619297-52b84700-b90e-11e9-8def-852fd4caff5f.png)
