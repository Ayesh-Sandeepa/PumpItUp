## PumpItUp

This is a model trained using RandomForest to the Pump It Up, Data Mining Water Table Competition. 

In the data preprocessing part,
1) First the missing data are imputed, for the categorical data the missing values are imputed as a seperate value as "Missing"
and for the numerical data the missing values are replaced from the mean of each column.
2)Then identify the columns where there is a high correlation between any two columns.
3)And according to those observations, and with manual observations, the columns are important to train the model are selected. 
3)Finally, the categorical columns are encoded using Label Encoding.


Next, for the training I use RandomForesetModel with 300 estimators. And it is used finally to predict the functionality of the pipes in the test set.


![This is an image](/assets/Pump_It_UP.png)


