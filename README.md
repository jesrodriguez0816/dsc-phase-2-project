# Kings County Housing Project
### Jessica Rodriguez
### Email: jessicallowell@gmail.com
### GitHub: @jesrodriguez0816

## Summary

The goal of this project was to create a linear regression model that predicts housing prices in Kings County, Washington.
Housing data spanning from 5/2014 - 5/2015 was provided. Exploratory Data Analysis was used throughout this project. Statistics and and visualizations were used to identify and analyze linearity assumptions and data distributions.
### The main question addressed was: Which housing attributes had the greatest effect on price?


## Business Value
This project’s predictive model can be used by real estate agents and brokers, in addition to their domain-specific knowledge, to predict trends and housing prices.

The model can also be used by home-buyers and sellers in their decision-making processes.


## Methods
Exploratory Data Analysis (EDA) was used for this project.

‘Price’ was our target variable. We compared this variable to various housing features in the data set.

Special consideration was given to location, square footage, condition, grade and amount of bedrooms/bathrooms.
![alt text]("Image 2-11-22 at 8.40 AM.jpg")


## Modeling
The following models were created for this project:

A simple linear regression model compared our target variable (price) to the following continuous features: square footage, flooring, and year built. Administering a recursive feature eliminator and KBest test, had a negative impact on the model.

A polynomial regression model where degree = 2.

The polynomial regression model had the best R-squared testing result and lowest mean-squared error, and therefore was saved as the best fit model.


## Results
### The following home features had a high correlation with price:
- Home square footage
- Amount of bedrooms and bathrooms
- Home locations.
    - Highest-priced zip codes: Medina,  Bellevue, Mercer Island,  Capital Hill
    - Lowest-priced zip codes: Normandy Park, Burien, Auburn, Kent, Seatac
- Condition and Grade (based on Kings County housing system)
![title]("img/picture.jpeg")
![alt text]("Image 2-21-22 at 11.57 AM.jpg")
![alt text]("Image 2-21-22 at 11.57 AM (1).jpg")
![alt text]("Image 2-21-22 at 11.57 AM (2).jpg")
![alt text]("Image 2-21-22 at 11.58 AM.jpg")
![alt text]("Image 2-21-22 at 11.57 AM.jpg")

## Next Steps

For next steps, I would analyze the detailed geography of the Kings County.
I would specifically look at the proximity to certain zip codes to schools, amenities, public transportation, etc.
I would also analyze census data to see how demographics affect housing prices.

