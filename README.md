# Regression-Project
In this project, I will document the stages I went through to predict store sales on data from Corporation Favorita, a large Ecuadorian-based grocery retailer.

Specifically, I built a model that more accurately predicts the unit sales for thousands of items sold at different Favorita store

## Dataset
The training data includes dates, store, and product information, whether that item was being promoted, as well as the sales numbers. Additional files include supplementary information that may be useful in building your models

|File| Data Desription|
|---------------------------|---------------------------------------------------|
|train.csv|The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales|
|store_nbr |identifies the store at which the products are sold.
|family |identifies the type of product sold.
|sales |gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).
|onpromotion |gives the total number of items in a product family that were being promoted at a store at a given date.
|test.csv|The test data, having the same features as the training data. You will predict the target sales for the dates in this file.
The dates in the test data are for the 15 days after the last date in the training data.
|transaction.csv|Contains date, store_nbr and transaction made on that specific date.
|sample_submission.csv|A sample submission file in the correct format.
|stores.csv|Store metadata, including city, state, type, and cluster.
|cluster| is a grouping of similar stores.
|oil.csv|
|Daily oil price|includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and its economical health is highly vulnerable to shocks in oil prices.)
|holidays_events.csv|Holidays and Events, with metadata
## Hypothesis & Questions

The questions below are to be answered. Do note that, you are free to draw more hypothesis from the data.

Is the train dataset complete (has all the required dates)?

Which dates have the lowest and highest sales for each year?

Did the earthquake impact sales?

Are certain groups of stores selling more products? (Cluster, city, state, type)

Are sales affected by promotions, oil prices and holidays?

What analysis can we get from the date and its extractable features?

What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)











## Author

`Gilbert Botchway`

- [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gilbert-botchway/) 

- Read more on my [medium](https://medium.com/@botchwaykojo/predicting-unit-sales-for-favorita-stores-using-machine-learning-b80b5722bf60)
