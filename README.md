# Project Name
Linear Regression Assignment - Bike sharing data using ML

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike >share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the >system unlocks it. This bike can then be returned to another dock belonging to the same system.

- What is the background of your project?
>A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding >it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its >revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

>In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the >nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand >out from other service providers and make huge profits.

- What is the business probem that your project is trying to solve?

>Required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market

- What is the dataset that is being used?
>Bike Sharing dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
<ul>
    <li>The R² value for the test data = 0.820;</li>
    <li>The R² value for the train data = 0.824;</li>
    
</ul>
we can see the value from the final model summary above. 

Since the R² values for both the train and test data are almost equal, the model we built is the best-fitted model.

Data Analysis:-
The features that are profitable for rentals:- 
<ul>
<li>Year</li>
<li>Temp</li>
<li>weathersit_Sunshine</li>
</ul>
The features that are unprofitable for rentals:-
<ul>
<li>Humidity</li>
<li>weathersit_Rain</li>
<li>Wind Speed</li>
</ul>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Pandas 1.2.4
- Numpy 1.20.1
- seaborn 0.11.1
- matplotlib 3.3.4
- statsmodels 0.12.2
- sklearn 0.24.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
NA

## Contact
Created by [@ganeshbabuNN] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
