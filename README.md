# Project Name
> Regression model to predict the price of houses in Australia.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- US based Surprise Housing Company is planning to expand in Australia Market. So they want to build a model to predict the top features determining the price of the house.
- House price prediction and feature improtance for price calculation.
- Australia Housing price dataset, collected by Surprise Housing company.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- I got very close ridge and lasso regression models, so any of them can be used finally.
- I will use Ridge Regression with regularization hyperparameter value of of 1 (defalt value) even though I got better training results at alpha value of 0.3. This is beacuse of the first default model generalizing well.
- I will use Lasso with regualarization hyperparameter value of 100. It was performing good for both train and test sets.
- I did identify and rank the features for ridge nad lasso that were important for making predictions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas==1.5.3
- numpy==1.22.3
- scikit-learn==1.2.1
- seaborn==0.12.2
- matplotlib==3.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@Pushkarkv] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->