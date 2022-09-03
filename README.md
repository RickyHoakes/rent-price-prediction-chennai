# Rent price prediction chennai

The price of the house is completely decided by the owners/brokers, If the pricing is not effective,then the amount of people approaching to buy/rent the house is decreased. so, with our model it can help both tenants and seller by giving better price considering all the factors mentioned above. so, it can increase the chances of selling/buying the property leading to more robust economic growth.

# Methodology
We collect website data from nobrokers.in,then using webscraping methods i.e 
datacollecting,cleaning and labelling, we make our owndataset.
Once we have the dataset, all the factors(amenities,apartment type,location,builtupsize ,Desposit , 
furnishing and so on) are the variables that caninfluence the property pricing depending on their 
importance.

We evaluated our data using various models

(i) Linear Regression

(ii) Random forest.

(iii) Gradient Boosting.

(iv) XGBoost. 

We used RMSE(Root mean square error) and MAE (Mean Absolute Error) for computing error 
produced by each models. Out of which XGBoost gave better accuracy with least error. 
So we used to XGBoost Regressor to predict the prices of the property.

# Details of all the experiments conducted

# [1] Experiment – I:

Data Scraping:

We have collected the data from the rental website using python 
Libraries Used (for Mining): BeautifulSoup, Requests DATA.csv
We have over 1000 datapoints for our dataset which is vital for prediction of our rent prices. 

Dataset:

![image](https://user-images.githubusercontent.com/89961380/188273990-90ae77ed-477d-4c3f-aabc-ce4fc56b5730.png)

PseudoCode:(Data Mining):

Initialize Libraries: AssignParameters:(Title ,type , deposit , size , rent ) 

Initialize the URL: Parse the Website Page source using BeautifulSoup 

Find the Classes of the Parameter and append to the parameters

Write the Lists to CSV file.

Label the CSV according the parameters .

# [2] Experiment – II:

Model training and model comparisions: Linear Regression, Random forest, Gradient Boosting,XGBoost. 

We compared all the models for best model suitable for the obtained dataset for predicting the 
rent/property prices. We conducted several data visualization plots for the dataset, for identification of most important 
attributes of the data.

We gathered accuracy and error for each model using RMSE and MAE, then we chose the best 
model that gave the best accuracy with least error.

We used that model for predicting the prices for the property.

We tried this on this experiment on self-made scraped dataset.

# Procedure:

Obtaining Data

Training Various models with our data

Testing various models to check which models gives better accuracy

Best model is chosen for predicting the property/rental prices

# Inferences from the experiment

![image](https://user-images.githubusercontent.com/89961380/188274133-67554c81-547c-4b79-841d-c8be9e4ab3ac.png)

# Using RMSE

![image](https://user-images.githubusercontent.com/89961380/188274144-c801c34e-83f4-421f-9605-c50fc70a5422.png)

# Using MAE

![image](https://user-images.githubusercontent.com/89961380/188274155-0c28a4b8-638e-450f-b40c-590638eb01fd.png)

We compared all the models for our dataset and XGBoost gave us the best result among all the 
models, we also got least error with RMSE and MAE.

# Solution of the problem

The price of the house is completely decided by the owners/brokers, If the pricing is not effective,
then the amount of people approaching to buy/rent the house is decreased. 

so, the solution of the above problem is that with our model that gave the best fit for the data, we 
can help both tenants and seller by giving better price considering all the factors mentioned above. 

This can increase the chances of selling/buying the property leading to more robust economic 
growth.

# Validation/comparison of the results

Importance of various attributes contributing to the prediction of prices.

(i) Linear Regression

![image](https://user-images.githubusercontent.com/89961380/188274195-8215429b-90c1-45c8-9007-87cbaf5f8c52.png)

![image](https://user-images.githubusercontent.com/89961380/188274200-9eec773c-f2a2-4c20-a15e-e4e7709d052c.png)

(ii) Random forest

![image](https://user-images.githubusercontent.com/89961380/188274218-268bb337-bfb1-4b19-84d5-1c672ebc8016.png)

![image](https://user-images.githubusercontent.com/89961380/188274223-2cc79711-dbe5-4ae9-b80b-e0bbc94aefff.png)

(iii) Gradient Boosting

![image](https://user-images.githubusercontent.com/89961380/188274236-53491229-cc46-4c55-840f-011395fda994.png)

![image](https://user-images.githubusercontent.com/89961380/188274241-a63fd848-7230-4b41-a7da-4eee7bcd1e6e.png)

(iv) XGBoost

![image](https://user-images.githubusercontent.com/89961380/188274252-676b4f80-08f5-49de-9444-69dcdda3a3a0.png)

From the above analysis, we can find the important attributes that are affecting the pricing of the 
property, this helps in finding the right price for the property, depending on various factors like 
semi-furnished or fully furnished, 2BHK or 3BHK or property age etc…

# Methodologies adapted by different people, for the same problem:

All the charts exhibit the expected relationship between the features and the housing prices.

![image](https://user-images.githubusercontent.com/89961380/188274281-e825bc77-9ece-42ec-b2b7-18e3cb800668.png)

The results are then evaluated by the MSE, RMSE and MAPE criteria. These values are estimated to 
be 0.01423, 0.11929 and 0.54571%, demonstrating that SVM fits their data very well. Following this 
is the estimation of stochastic gradient descent. Employing 5 CV, it takes 37 epochs to converge in 
0.05 seconds.

# Impact of the Project
Our project can help both tenants and seller by giving better price considering all the factors 
mentioned above. so, it can increase the chances of selling/buying the property. 

It can also help researchers by our visualizations and comparisons of various models used for 
predictions, they can know pre-hand which model has the higher change of giving better accuracy.

It can help normal people like us with keeping us updated about the prices at various places.

# Scope of converting the project to a Research article /Product

We can convert our project as product, as a notifier of prices of various locations based on the 
request, due to its effective pricing process, it can give genuine prices for all the customers, this 
helps all the users understand the pricing of the properties at various places.

For research article, it can help researchers with our visualizations, and comparisons, which they can 
use for their project.






