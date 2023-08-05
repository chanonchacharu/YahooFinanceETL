
# Yahoo Finance ETL

The aim of this project is to getting the understand of how ETL (extract, transform, and load) process work. I decided to get the data from Yahoo Finance API. 

Currently, some of the ETL process like Load isn't followed the its conventional approach. For instance, I don't have database to store the data; hence, I stored the data separately into smaller partition in the format of Spark Dataframe. 

If you have any suggestion, please let me know!

### Installation
In order to use PySpark on [Kaggle](https://www.kaggle.com/), it must be installed by typing the following command `!pip install pyspark` into one of the cell.

Additionally, `yfinance` library must be installed using the command `!pip install yfinance`.

#### By: Chanon Charuchinda
