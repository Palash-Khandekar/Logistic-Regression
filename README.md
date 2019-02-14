### Predicting who buys car using Logistic Regression model

In this project, I am creating a Logistic Regression model to predict the users who may buy  car. The variables for prediction are "Age" and "Salary" of the users. I have split the data into training and testing set in the ratio 3:1. 
This model can be used by business to target advertisements on group of users.

### Visualization of test model
The goal here is to classify right users in right categories. We see there are two prediction regions in the plot(Red and green). Red region indicates the user who did not buy car and green region indicates user bought car.

The line separating the two classifiers is known as prediction boundary.

* Orange points indicate the users who bought car
* Blue points indicate the users who did not buy car

##### Result
* young users with low salary did not buy car
* few young age users with higher salary also bought the car
* users with higher salary and older in age bought the car
* users with lower salary and older in age also bought the car

We see there are wrong prediction points in the plot(orange points in red region,  blue points in green region)

I used confusion matrix to calculate the accuracy of the model which is about 88%.
![image](https://user-images.githubusercontent.com/41500507/52821779-742e2980-3075-11e9-886f-6a793eca9c1f.PNG)





