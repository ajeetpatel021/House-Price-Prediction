# House-Price-Prediction

Took dataset from kaggle of city bangelore, given below are the features of that dataset <br>
<b>area_type - type of area<br>availability - date of availability<br>location - location where the flat located<br>size - size in BHK<br>society - name of society<br>total_sqft - size in square feet<br>bath - Number of bathrooms<br>balcony - Number of balconies<br>price - Price of house</b>

<h2>Data Cleaning</h2><br>
Did data cleaning, handled missing values, feature engineering<br> There were some feature columns where I had to do one hot encoding <br>
<h2>Model Selections & Training </h2><br>After cleaning the dataset I tried multiple regression models from <b>sklearn</b> and choose<b>XGboost</b> it gave less MSE and higher Accurecy between all of them

<h2>Accuracy and MSE </h2><br>
Model Score - 0.91<br>
MSE - 26.58
