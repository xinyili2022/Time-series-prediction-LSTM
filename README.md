# Time-series-prediction-LSTM
Update in Nov.08
The "End..." pdf and ipynb file is the version considering recursive predition. The input of the sequence is the prediction of last sequence, that is the whole prediction based on the previouvs prediction, and there was not exteror factor added in. It could show the potiential results without the special events.

Here is the explanation of the three ipynb files. 

"HW_...." is the one without adjusting the model to the best one. I forgot to do this step at first, and you could ignore the "HW_..." file;
<br>The one "Updated_..." is the version after updating the best model and being uploaded this Monday. While, the understanding of time lag in  this version is that, for example, when time lag=5, using the previous FIVE DAYS' stock prices to predict the price of today;
<br>The one "Final_..." is the version updated this Thursday, and the understanding of time lag here is using the stock in the previous FIFTH DAY to predict the price of today.

Also, for the pdf file, which is actually slides, the comparison in both of the various understandings of Time Lag will be introduced.
