# Bike Sharing Assignment (Multiple Linear Regression)
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.


## Table of Contentss
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Model Building and Prediction](#model-building-and-prediction)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. 
>> 1. From the analysis company wants to know few of these factors : <br>
    1. Which variables are significant in predicting the demand for shared bikes.<br>
    2. How well those variables describe the bike demands <br>

- Business Objectives :
>> 1. A efficient model needs to be build to find the variables which are significant the demand for shared bikes with the available independent variables.
>> 2. The model will be a good way for management to understand the demand dynamics of a new market.
>> 3. Management can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.


## Model Building and Prediction
- Data Cleaning and analysis
> - Null value check and outliers treatment is performed on the data.
> - As part of EDA, pariplot and correlation heat map among variables is compared. Box plots compared for the categorical variables and regression plots for numerical variables.
- Data preparations
> - Dummy variables created using pandas.
> - Data is splited into train and test sets, using sckitl learn libraries
> - Train data fitted and transformed using MinMaxScaler, Test data is scaled and transformed also.
> - Data is splited into train and test sets, using sckitl learn libraries.

- Modelling the data
> - Recursive Feature Selection used to sort out primary significant features for the model.
> - Liner Regression model is fitted and stats predicted using Stats Models api.
> - Best fit model identified and test data predicted on the data set.
> - Final model prediction results calculated based on R2 Score ( R Square adjusted value) and features coefficients vlaues.


## Conclusions
- R2 score value for predictions on test data (0.797) and R2 score value of train data(0.829). Those two R-Squared values not much differ from each other then is difference of 2-3%, hence we can see our model is performing good even on unseen data (test data)
- Bike Sharing demand is high during month of September, so company should expand their business in that time.
- We can conclude that from the analysis it is clearly shown the business will follow the growth curve, so once the situations goes back to normal, company should more focus on customer and other features to expand their business on a large scale.
- Significant variables identified.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - PYTHON
- library - PANDAS
- library - NUMPY
- library - MATPLOTLIB
- library - STATSMODEL
- library - SKLEARN


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@Soumayad96] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->