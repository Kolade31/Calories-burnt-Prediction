# Calories-burnt-Prediction
To Predict the number of calories a person has burnt during a workout based on some biological measures.

##Introduction
For this project I used two dataset named "exercise"  and "calories". The exercise dataset contains variables such as the body temperature, the heartbeat, the height, weight, gender and age of the person  while the "calories" dataset contains the number of calories burned. Seven regression algorithms are used to predict calories burned depending on the workout duration,body temperature,height,weight and age of the person.

##Data Source
I got my data source for this project from haggle. Here is the link;  https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos?select=exercise.csv

##Dataset description 
With the combination of the two datasets used in this project, a new dataset was formed which has 8 features, one  variable, and 15000 instances. 

##EDA
Some of the insights I could get from the EDA performed on the analysis include:
1.The average height of the boys is higher than girls.
2. The weight of the girls is lower than that of the boys.
3. There is an almost identical distribution of male and female data points. 
4. The distribution of the continuous features is close to a normal distribution except for some features like Body_Temp and Calories.

##Feature Engineering
There is a serious problem of data leakage as the duration of exercise feature is highly correlated with the target column which is calories. So, I had to drop it along with Height and Body_Temp features.

##Conclusion
Of the seven regression algorithms, LGBM Regressor had the lowest Mean Absolute Error.

