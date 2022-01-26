# Kings County Housing Project
### Jessica Rodriguez
### Email: jessicallowell@gmail.com
### GitHub: @jesrodriguez0816

## Summary
The goal of this project was to create a linear regression model that predicts housing prices in Kings County, Washington.

Housing data spanning from 5/2/2014 - 5/27/2015 was provided. The Cross-Industry Standard Process for Data Mining (CRISP-DM) was used throughout this project. Statistics and and visualizations were used to identify and analyze linearity assumptions and data distributions. The retained model predicts housing prices on test data with a ~$251,000 margin of error.


### The main questions addressed were: What attributes of the data contributed to higher housing prices, and which attributes had the greatest effect on price?

## Business Value
This project’s predictive model can be used by real estate agents and brokers, in addition to their domain-specific knowledge, to predict trends and housing prices.
The model can also be used by home-buyers and sellers in their decision-making processes.

## Methods
The Cross-Industry Standard Process for Data Mining (CRISP-DM) was used for this project.
‘Price’ was our target variable. We compared this variable to various attributes in the data set (see: column names and descriptions below).
Special consideration was given to location (zipcode), square footage and amount of bedrooms and bathrooms.
![image info](./pictures/image.png)

Basic descriptive statistics were visualized through scatter plots to understand linear relationships with the target variable. Histograms were created to view data distributions and to identify outliers, which were handled on a case by case basis. Once basic data cleaning was done, some statistical tests were administered to get a better understanding of the significance of assumptions analysis process.

The data was split into separate training and test sets. The lack of significant difference between output of train and test split allowed for the assumption the model that was not over fit. The bmodel was then fit to the entire data set and was saved for future use.

## Results
Total square footage of living space, number of bedrooms/bathrooms and location had a high influence on price. Grade , which was the overall grade given to the housing unit, was also a strong indicator of price. If grade scored well it was a more accurate price indicator. This model predicts within ~$250k of housing prices in Kings County, Washington. The model is $406 off on average with each prediction.

## Next Steps
For next steps, I would analyze, in greater detail, the geography of the Kings County, Washington. I would specifically look at the proximity to certain zip codes to schools, amenities, public transportation, etc. I would also analyze census data to see how demographics come into play with housing prices.
