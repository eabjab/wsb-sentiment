# wsb-sentiment

### The following notebook files are included: 

- encoding - Contains the data aggregation and pre-processing for Reddit posts and the NLP (Doc2Vec) model that trains the Reddit post data. Training the model is quite lengthy so we avoid running it unless you wish to build a new model (a previous model file is in the Google Drive). Fetching the Reddit data of the 10 stock tickers is also quite lengthy as well.
- rnn - Contains the recurring neural network (LSTM) model. This is the file that should be run. It requires three pickle files and the price CSV for each stock ticker: the vectorized posts, daily upvotes, daily volume, and the CSV containing the closing price. 
- stock_api - Fetches the financial data from the Polygon API from a start and end date. Only used for data aggregation.
