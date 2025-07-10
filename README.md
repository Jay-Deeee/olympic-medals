This is a personal small project to kickstart my journey to learn Python and coding Machine Learning scripts. This specific project aims to predict how many olympic medals a country will win in a year based on past data. 

It will be trained using previous years' data of how many medals each country won and how many athletes they entered, then using that same template for testing where after predictions are made (using athletes entered and medals won in the previous year) will compare those predictions with the latest year where error is the absolute value of medals won - medals predicted.

Packages used:
pandas
numpy
scikit-learn
seaborn
ipykernel

Conclusion:
Using medals won in prev years and athletes entered for each country was only acceptably accurate for countries that entered a high number of athletes, for countries with low entrants, the results were far less accurate. For future use, maybe taking into account the individual athletes performance in pervious years (if any) would allow for more accurate predictions.
