This project  is a **Machine Learning based Web Application.** It can detect whether *the Car Price of Yours*.
This web application was diployed in Amazon Web Services(AWS).
You can view the app here (http://carpriceprediction-env-1.eba-k8asyuv3.us-east-1.elasticbeanstalk.com/)



# Car Valuation:India:
![GIF](static/images/car_valuation.png)

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

## Demo
- I have deployed this on AWS platform
Link:![image](https://user-images.githubusercontent.com/91062741/164026906-5e87364e-34f1-4aef-b34e-8a6ecb66828d.png)


## How to use
- Select any car fill the inputs with proper information then click on predict button you will get predicted price of that car.

## Deployment
#### Prepare a configuration file in main directory
1. Create .ebextensions folder to your main directory
2. Inside .ebextensions folder create a python.config file and write configration like [this](https://github.com/jaysoftic/car-valuation/blob/main/.ebextensions/python.config)
3. Create .ebignore file inside main directory

#### Here's simple steps to create an application on Amazon Web Services(AWS)
1. i was deployed the web application in the AWS
2. Enter your application name.
3. Application tags are optional so just ignore it.
4. For Platform, choose a python platform.
5. For Application code choose Upload your code.
6. Upload a zip file of your project.
7. Click on create application button.

- rest of things will take care by aws elastic bean stalk and you will get deployed link.

## Technologies Used
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>
<code><img height="30" src="https://symbols.getvecta.com/stencil_80/56_flask.3a79b5a056.jpg"></code>
<code><img height="30" src="https://d1.awsstatic.com/icons/console_elasticbeanstalk_icon.0f7eb0140e1ef6c718d3f806beb7183d06756901.png"></code>

<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg"></code>
<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/330px-Scikit_learn_logo_small.svg.png"></code>

## Team
 Nithya![image](![image](https://user-images.githubusercontent.com/91062741/164396101-91a4f045-7b77-4479-9b37-cdec3155a287.png))
 (https://www.linkedin.com/in/nithya-bhujangarao-ab6747223/)
 [Nithya](https://www.linkedin.com/in/nithya-bhujangarao-ab6747223/)


## 
- ## The world needs strong women. Women who will lift and build others, who will love and be loved, women who live bravely, both tender and fierce, women of indomitable will
