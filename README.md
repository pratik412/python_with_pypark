# python_with_pyspark
I have used Small_Car_Data’ dataset. The data contains 11 columns comprising of both categorical and numerical variables.
Then I have removed the header of the attached Samll_Car_Data.csv file and then imported it into Spark. 
Randomly selected 10% of you data for testing and use remaining data for training. Looked initially 
at horsepower and displacement. Treat displacement as a feature and horsepower as the target 
variable. Used MLlib linear regression to identify the model for the relationship  and used test data to 
illustrate accuracy of your ability to predict the relationship. 
Then used the Vector Assembler function which is available in the Pyspark ML Feature library to convert the feature ‘Displacement’ and target ‘Horsepower’ in Vector form so that we can use MLib to create a model from it. and get to kno from the scatter plot between the Horsepower and Displacement that the Actual values are really close to the Predicted Values and the Regression Line is a good predictor for the Horsepower of the car.
Then I have treated cylinders, displacement, manufacturer, model year, origin and weight as features and used 
linear regression to predict two target variable: horsepower and acceleration. Here some of the variable are categorical variables.As the Linear Regression Model can only handle numerical variables, Hence encoded the categorical variables using ordinary encoding ‘Model’ and ‘Manufacturer’ that we will be using  as features for the prediction of our Target variables. And after that analyzed that which of target variables is easier to predict, in the sense that predicted values differ less from the original values

