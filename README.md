# car-price-prediction
CAR PRICE PREDICTION APPLICATION
Introduction
The objective of this project to make a end to end machine learning project and help others in figuring out their old car's selling price.

Hence,for instance, we get data from the car website CarDekho.com, filled with information on a wide variety of cars, including their selling price and present price. We realize that we can use this data to make sure we get a good deal on a new car. In particular, we can figure out exactly how much one should pay for a specific type of car.

About the dataset
This dataset contains information about used cars listed on www.cardekho.com This data can be used for a lot of purposes such as price prediction to exemplify the use  of linear regression in Machine Learning. The columns in the given dataset is as follows:

Car_Name
Year
Selling_Price
Present_Price
Kms_Driven
Fuel_Type
Seller_Type
Transmission
Owner

I have used the RandomForestRegressor to solve this ML problem.
Credit: www.kaggle.com
This project is a Machine Learning based Web Application. It can detect whether the Car Price of Yours. This web application was diployed in Amazon Web Services(AWS).

Car Valuation:India:
GIF

The Car Valuation project is about predicting selling price of used cars
This web application have 2040 unique cars and it can predict selling price of that cars in INR
Overview
Here i have 8218 records of cars and it's features in which 2040 are unique cars
Here i have trained various model using hyperparameter tunning and it took 80.42 minutes on intel i3 processor
After training a model i got Gradient Boost as best model for this problem statement
Gradient Boost algorithm gives 0.977921 r2_score it means 97.79% accuracy on training data set and 0.986117 r2_score it means 98.61% accuracy on testing data set, here data set was split on 80:20 ratio
Here i have developed end to end application using Flask, Javascript, Bootstrap, CSS and HTML
I have used google-images-download library to scrap links of images from google images.
Data Source
In this project i have used cars dataset from kaggle, you can get it from here
Demo
I have deployed this on AWS platform Link:image
How to use
Select any car fill the inputs with proper information then click on predict button you will get predicted price of that car.
Deployment
Prepare a configuration file in main directory
Create .ebextensions folder to your main directory
Inside .ebextensions folder create a python.config file and write configration like this
Create .ebignore file inside main directory
Here's simple steps to create an application on Amazon Web Services(AWS)
i was deployed the web application in the AWS
Enter your application name.
Application tags are optional so just ignore it.
For Platform, choose a python platform.
For Application code choose Upload your code.
Upload a zip file of your project.
Click on create application button.
rest of things will take care by aws elastic bean stalk and you will get deployed link.
Technologies Used:
1.python
2.jupyter notebook
3.matplotlib
4.html,css
5.numpy
6.scikit language
7.java script
