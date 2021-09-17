# PumpItUp

This is a model trained using RandomForest to the Pump It Up, Data Mining Water Table Competition. 

In the data preprocessing part,
first the missing data are imputed, for the categorical data the missing values are imputed as a seperate value as "Missing"
and for the numerical data the missing values are replaced from the mean of each column.

Then identify the columns where there is a high correlation between them. And drop the columns identified as that have high correlation with other columns.

Then the categorical columns are encoded using Label Encoding.

This is how the preprocessing is done.

Next, for the training I use RandomForesetModel with 300 estimators. And it is used finally to predict the functionality of the pipes in the test set.

![A](./Pump It Up.png?raw=true "Title")
