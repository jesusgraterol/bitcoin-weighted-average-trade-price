# Bitcoin Weighted Average Trade Price

When trading Bitcoin, stocks or any other asset, it is very common to execute several trades at different prices for different amounts. Therefore, the mean of the prices won't suffice to derive the real entry price. The formula to calculate the weighted average price goes as follows:

![image.png](data:image/png;base64,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)

[View Notebook](./bitcoinweightedaveragetradeprice.ipynb)
