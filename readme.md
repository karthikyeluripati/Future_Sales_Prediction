# Future Sales Prediction using XGBoost

#### Sales prediction is the practice of foretelling the volume of goods or services a sales unit will sell over the course of the following week, month, quarter, or year in order to estimate future revenue. Future-focused topics dominate sales forecasting. Making accurate sales projections is crucial for a business.

#### Dataset- https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales/data

### Below is a list of the data contained in this project:
#### sales_train.csv: The training set. Daily historical data from January 2013 to October 2015.
#### test.csv: The test set. There is need to forecast the sales for these shops and products for November 2015.
#### sample_submission.csv: This is a sample submission file shown in the correct format.
#### items.csv: Supplemental information about the items/products.
#### item_categories.csv: Supplemental information about the items categories.
#### shops.csv: Supplemental information about the shops.


### Dataset Description
#### ID: An Id that represents a (Shop, Item) tuple within the test set
#### shop_id: Unique identifier of a shop
#### item_id: Unique identifier of a product
#### item_category_id: Unique identifier of item category
#### item_cnt_day: Number of products sold. You are predicting a monthly amount of this measure
#### item_price: Ccurrent price of an item
#### date: date in format dd/mm/yyyy
#### date_block_num: A consecutive month number used for convenience. January 2013 is 0, February 2013 is 1 and October 2015 is 33
#### item_name: Name of item
#### shop_name: Name of shop
#### item_category_name: Name of item category