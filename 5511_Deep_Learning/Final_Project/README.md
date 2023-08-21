### Project Overview

Built an LSTM model using time series transaction data from a single retailer. The data can be found on Kaggle [here](https://www.kaggle.com/datasets/mathchi/online-retail-ii-data-set-from-ml-repository)


### Data Overview

The data contained invoice transaction history for a single retailer for transactions made from 2009-2011. The main fields from the data used for this project were the Invoice data, quanity of items sold, and price. Here is a brief description of all data fields:

- InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invice date and time. Numeric. The day and time when a transaction was generated.
- UnitPrice: Unit price. Numeric. Product price per unit in sterling (Â£).
- CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal. The name of the country where a customer resides.


### Modeling

- LSTM with varying architectures and two different lookback periods

