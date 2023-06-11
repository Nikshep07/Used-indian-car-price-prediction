

#### The Car Valuation project is about predicting selling price of used cars
#### This web application have 2040 unique cars and it can predict selling price of that cars in INR

## Overview
- Here i have 8218 records of cars and it's features in which 2040 are unique cars
- Here i have trained various model using hyperparameter tunning and it took 80.42 minutes on intel i3 processor
- After training a model i got **Gradient Boost** as best model for this problem statement
- Gradient Boost algorithm gives **0.977921 r2_score** it means **97.79%** accuracy on training data set and **0.986117 r2_score** it means **98.61%** accuracy on testing data set, here data set was split on 80:20 ratio
- Here i have developed end to end application using Flask, Javascript, Bootstrap, CSS and HTML
- I have used [google-images-download](https://pypi.org/project/google_images_download/) library to scrap links of images from google images.

## Data Source
- In this project i have used cars dataset from kaggle, you can get it from [here](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho?select=Car+details+v3.csv)

## How to use
- Select any car fill the inputs with proper information then click on predict button you will get predicted price of that car.

## Deployment
#### Prepare a configuration file in main directory
1. Create .ebextensions folder to your main directory
2. Inside .ebextensions folder create a python.config file and write configration 
3. Create .ebignore file inside main directory


- Car images credits goes to google-images-download and google images search engine

## 
- If you like my work and it helped you in anyway then please do ⭐ the repository it will motivate me to make more amazing projects
