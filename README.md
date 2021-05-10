# Final-Project-606

This project is based on healthcare data , where the dataset is from years 2005-2015(10 years) data of top 5 main causes of deaths in United States.  My project is to predict the accuracy of death rate using ML algorithms. 

So the project was held in a series of various steps through which the accuracy was found. 

1. Data Clean: First step is to clean the obtained dataset by removing null values , and replacing them either with 0 or removing them from the dataset. 

2. Data Analysis: In this step the attributes of dataset is compared with each other to idetify which paramters will be helpful to apply in the machine learning algorithms along with there dependances that helps to pull a meaning full data to apply the algorithms.4

3. Build Models: In this project the prediction was made by applying various kinds of regression models, The selected models are:
      1. Linear Model:  For this model the paramters [population , Expexted Deaths , Observed Deaths] of dataset is selcted and in which the these three accuracies are obtained :
                  1. Overall Accuracy of deathrate. 
                  2. Regional accuracy
                  3. Vareience in Deathrate .
                  For these to obtain the expected and observed deaths are combined and loaded as a single new column in the dataset. The accuracy obtained for the regression is between 50 - 54 % for this model . The same method was applied for remaing three models which have accurracies of :
                  
    2. Lasso : It has 48 % of accuracy 
    3. Ridge: It has 47% of accuracy
    4. Elastic Net : This is the lowest which has 39% of accuracy 

So from the above comparsions , it can be detremined that Linear regression has provided a better accuracy when compared to other regression models .
