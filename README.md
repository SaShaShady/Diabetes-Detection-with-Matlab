# Diabetes-Detection-with-Matlab
A project which detects diabetes using the Support Vector Machines in Matlab

STEP 1----------------------------------------

Data Set and Feature Engineering:
I got the dataset from Kaggle : https://www.kaggle.com/uciml/pima-indians-diabetes-database
On this Dataset, I did some Feature Engineering such as 
a. Checking if there is any null value present
b. Scaling the features
c. Handling the null and 0 values present in the dataset and replacing them with the average value of that column
d. Repeating the same steps for the test data set as well. 

STEP 2---------------------------------------

Over here, I call the fitcsvm model from MATLAB and train our dataset.

STEP 3---------------------------------------
Once done with training, we now test the model. In the picture we can see that this approach gave me 80% 
Accuracy!![accuracy](https://user-images.githubusercontent.com/51987596/131337469-c6dfed39-b92e-4bb4-89ee-dc801defa589.png)

