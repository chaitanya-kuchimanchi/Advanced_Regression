# Advanced_Regression
> BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset of housing sales is provided by the team.
- Need to identify the significant variables that drive the dependant variable.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Linear regression seems to be overfitting with R2 96% on Training data and -1.1 R2 value on test data.
- Ridge seems to be working good on the data with Ridge 94% on Training and 90.5% on test
- Lasso also seems to have similar values as Rideg with 92.5% on train data and 90.3 on test data.

Important variables
1. When using Ridge model, GrLivArea, OverallQual, 1stFlrSF, OverallCond and TotalBsmtSF
2. When using lasso model  GrLivArea, OverallQual, OverallCond, TotalBsmtSF and YearBuilt

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pyhton - version 3.7
- Pandas - version 2.0
- Seaborn - version 12.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
The data set is provided by Upgrad.


## Contact
Created by [@chaitanya-kuchimanchi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->