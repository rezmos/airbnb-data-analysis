# Airbnb data analysis
This project was done to learn more about data analysis and how to do predictions.


## Quick-start
1. Clone the repo: `https://github.com/rezmos/airbnb-data-analysis.git`
2. blog:  https://medium.com/@rezmos/airbnb-pricing-data-analysis-for-boston-hosts-bab34622d62f

## Libraries
- pandas
- matplotlib.pyplot
- numpy
- seaborn
- sklearn (linear_model, model_selection, metrics)

## Files

- airbnb_boston_data_listing.ipynb
:In this file was done all data analysis corresponding to base price.

- airbnb_boston_data_predict.ipynb
:In this file was done all data analysis to predict base price.

## Summary 

-  Boston hosts can find some exciting responses to the first question. More than 60% of guests prefer to rent the entire house or apartment, and more than 30% private rooms. Shared rooms and hotel rooms are not desired to be rented by guests.
The precise property/space types leaders are Entire home/apt and Private Room.
- the Entire home/apt has a range price value between 235.9 and 299.7, while the Private room has a range price value between 96.94 and 156.9.
- A fund with a low R-squared, at 70% or less, indicates the security does not generally follow the movements of the index. Even when It was used imputation methods to predict the missing value, before drop all rows with nan information in every column.

