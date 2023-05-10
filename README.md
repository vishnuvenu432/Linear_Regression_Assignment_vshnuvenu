# Linear_Regression_Assignment_vshnuvenu
> 
The project involves building a multiple linear regression model to predict the demand for shared bikes based on various factors. The dataset includes information on daily bike demands across the American market based on several factors such as weather conditions, day of the week, month, and season.

The first step in the project is to perform data preparation, which involves checking the quality of the data, handling missing values and outliers, and converting categorical variables to dummy variables. After that, exploratory data analysis is performed to gain insights into the relationships between the variables and identify any patterns or trends in the data.

Next, we split the dataset into training and testing sets and use the training set to build a linear regression model to predict the demand for shared bikes. The model is evaluated using various metrics such as mean squared error, mean absolute error, and R-squared on the testing set.

Finally, we interpret the model coefficients and identify the significant factors that affect bike demand. This information can be used by the management to develop a business strategy to meet the demand levels and customer expectations, and to understand the demand dynamics of a new market..


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background:
The project aims to build a multiple linear regression model to predict the demand for shared bikes based on various factors. The bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. Due to the ongoing COVID-19 pandemic, many bike-share providers have suffered considerable dips in their revenues. Therefore, building an accurate predictive model can help such bike-sharing providers to understand the demand dynamics and create a mindful business plan to accelerate their revenue as soon as the pandemic situation gets better.
- Business problem:
The business problem that the project aims to solve is to understand the factors affecting the demand for shared bikes in the American market. The management of a bike-sharing provider, BoomBikes, wants to identify the significant variables affecting bike demands and prepare themselves to cater to the people's needs once the pandemic situation gets better all around.
- Dataset:
The dataset used in the project contains information on daily bike demands across the American market based on several factors such as weather conditions, day of the week, month, and season. The dataset has been sourced from a bike-sharing provider firm, and it consists of 730 observations and 16 variables. The target variable in the dataset is the total number of bike rentals, including both casual and registered users. The dataset includes both numerical and categorical variables. The categorical variables have been converted to dummy variables during the data preparation step.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1.	Weather conditions, particularly whether it is raining or not, have a significant impact on bike demand. The demand for shared bikes decreases significantly on rainy days compared to non-rainy days.

2.	The demand for shared bikes is higher during the summer and fall seasons compared to the winter and spring seasons. This could be because people are more likely to use bikes for recreational purposes during the summer and fall seasons.

3.	Weekdays have a higher demand for shared bikes compared to weekends. This could be because people are more likely to use bikes for commuting to work or school during the weekdays.

4.	The temperature and humidity have a positive and negative impact on bike demand, respectively. As the temperature increases, the demand for shared bikes also increases. However, as humidity increases, the demand for shared bikes decreases.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
•	Python programming language - version 3.0
•	Jupyter Notebook - version 1.0
•	Pandas library - version 1.3.3
•	NumPy library - version 1.21.2
•	Matplotlib library - version 3.4.3
•	Seaborn library - version 0.11.2
•	Scikit-learn library - version 0.24.2
