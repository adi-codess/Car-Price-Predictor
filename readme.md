# **Car Price Predictor**

#### A Machine Learning model that predicts the price of the car you want to sell on the basis of :

- Car Company
- Car Model
- Year of Purchase
- Fuel Type
- Kilometers Driven

## How to use?

1. Clone the repository
2. Install the required packages in "requirements.txt" file.
3. Run the Web Server in web.py file.
4. Open Localhost or 127.0.0.1:5000

Some packages are:

- numpy
- pandas
- scikit-learn
- flask

## How this project does?

1. First of all the data was scraped from Quikr.com (https://quikr.com)
   Link for data: https://github.com/rajtilakls2510/car_price_predictor/blob/master/quikr_car.csv

2. The data was cleaned (it was super unclean :( ) and analyzed.

3. Then a Linear Regression model was built on top of it which had 0.57 R2_score.

   Link for Original notebook: https://github.com/rajtilakls2510/car_price_predictor/blob/master/Quikr%20Analysis.ipynb

4. This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.

## Credits
- Original repository : https://github.com/rajtilakls2510/car_price_predictor
- Data File : https://github.com/rajtilakls2510/car_price_predictor/blob/master/quikr_car.csv
- Video Tutorial : https://www.youtube.com/watch?v=iRCaMnR_bpA&ab_channel=CampusX