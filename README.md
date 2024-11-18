# Melanoma Case Study
> Build a multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
    The project works on a solution that can evaluate images and alert dermatologists 
    about the presence of melanoma. This has the potential to reduce a lot of manual effort 
    needed in diagnosis.
- What is the background of your project?
    Melanoma is a type of cancer that can be deadly if not detected early. 
    It accounts for 75% of skin cancer deaths.
- What is the business probem that your project is trying to solve?
    To build a CNN based model which can accurately detect melanoma from provided pictures of melanoma.
- What is the dataset that is being used?
    The dataset includes pictures of melanoma disease sites categorized under several subcategories of melanoma.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Data rebalancing is a very important step to provide enough data points for training.
- Normalization, Rescaling are also two other important steps in model building
- Data rebalancing is achieved by Augmentation
- Rebalancing data set was important to solve underfitting of model.
- Not evaluated the test data set. Only evaluated based on validation set.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow 
- keras
- layers
- Sequential
- matplotlib
- numpy
- pandas
- PIL
- glob

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->