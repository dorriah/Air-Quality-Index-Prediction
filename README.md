# Air-Quality-Index-Prediction

This code shows training three ML models on the same dataset but using different parallization methods. 
There are five versions of the code as follows:
1- normal code with sequential execution.
2- parallel code using Ray API.
3- parallel code using threading.
4- parallel code using loky.
6- parallel code using multiprocessing.

parallel threading resulted in the shortest time for excuting the code and training ML models.
RF model resulted in the best performance with RMSE of 79.3.

The linke for air quality dataset: https://www.kaggle.com/rohanrao/air-quality-data-in-india
