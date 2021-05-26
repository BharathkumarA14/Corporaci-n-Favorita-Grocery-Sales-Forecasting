# Corporaci-n-Favorita-Grocery-Sales-Forecasting
Corporación Favorita Grocery Sales Forecasting using Machine Learning with Python(An End-To-End Case Study)
This Case Study is all about forecasting unit sales of items for the Ecuadorian supermarket chain 'Corporación Favorita'.
Corporación Favorita is a large Ecuadorian-based grocery retailer which operate hundreds of supermarkets, with over 200,000 different products on their shelves.

Objective -> Predicting the unit sales in future for thousands of items sold at different Favorita stores located in Ecuador.

Dataset used -> https://www.kaggle.com/c/favorita-grocery-sales-forecasting/data

Data Description
The training data includes dates, store and item information, whether that item was being promoted, as well as the unit sales. Additional files include supplementary information that may be useful in building your models.
· train.csv
Approximately 16% of the onpromotion values are NULL
· test.csv
Test data, with the date, store_nbr, item_nbr combinations that are to be predicted, along with the onpromotion information
· stores.csv
Store metadata, including city, state, type, and cluster.
Cluster is a grouping of similar stores
· items.csv
Item metadata, including family, class, and perishable.
Items marked as perishable have a score weight of 1.25, otherwise the weight is 1.0
· transactions.csv
The count of sales transactions for each date, store_nbr combination
· oil.csv
Daily oil price. Includes values during both the train and test data timeframe. (Ecuador is an oil dependent country and its economic health is highly vulnerable to shocks in oil prices)
· holidays_events.csv
Holidays and Events, with metadata
