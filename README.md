# Encoder-Decoder-cell-architecture-for-stock-price-prediction
A mildly insightful project about using encoder-decoder cells and combining them with other tools to predict financial stock prices.

This project came from an inspired reading of this post :
https://github.com/LukeTonin/keras-seq-2-seq-signal-prediction

This was an awesome post about using encoder-decoder cells to predict time series. I had been researching different methods to predict time series data, and this was one of the top posts I found.

While my problem didn't exactly fit with his implementation, Luke was extremely kind and helped me out with my data wrangling and how to essentially fit my data to the problem. 

I didn't end up using this for my actual work, since the process itself was slow and the results for my data weren't convincing enough to justify putting real money on it. 

Please excuse my terrible commenting on this python notebook. It's all done in steps, so its pretty self explanatory. 
Please feel free to comment on my work here, especialy where I went terribly wrong in my assumptions.

I also tried to include a few functions from the book "Advances in Financial Machine Learning" by Marco Lopez De Prado.These were mostly stationarity testing for the data and checking how much to fractionally differentiate the data to achieve stationarity while preserving the "memory" of the data. 

I personally found the book convincing, but the concept of stationarity vs memory , and the "dilemma", as the author calls it, didn't really stick with my analysis. Here's an article which talks about it in depth:
https://medium.com/pit-ai-technologies/non-stationarity-and-memory-in-financial-markets-4b8d1200667c

I hope you have fun trying to implement and improve the notebook!
