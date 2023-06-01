## System Overview

As an algorithm engineer, the first thing come to my mind is data. The first thing is to retrieval data from different sources, and then preprocess them into a format that can be used by the model. 

### Insights on Data: 
  -  Factors should be rich and comprehensive. If consider it in moderation/decision system way, it should be able to cover most of the factors and be devided into core features and none-core features with different groups. 
  -  Up to date: the feautre should be updated by an automatic feature retriever and so as the model. 
  - Comprehensive: able to deal with black swan events.

**What qlib data have**

Basically Qlib concenrates on the stock in both US an CN. Though the factors are not much, yet it is enough for a basic model.

The data contains the factors as well as all values of each stock. 
Each stock is saved as a CSV file. The date column is named 'date'. We can also get high/low, amount and the price of each stock.

Though this may not contains other factors, however, the way of using factors should be similar and it is a good point to start.