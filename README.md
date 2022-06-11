# FTX-Statistics

I created this script in order to evaluate the trading results of a friend, it is not perfect, but it allows to evaluate the money invested in the platform and your results if you left today.

**How to use the script**

Export your trades, deposits and withdrawals from the FTX website, you will have 3 csv files. Check and replace if needed the filenames in the notebook and run the notebook.  
At the end of the notebook, you will get the following values :
* wallet value : the values on your FTX accounts
* wallet 'out' value : the value difference between the in and out from your ftx account
* results : wallet value + wallet 'out' value
* fee sum : the sum of all the fee you paid

*warning :* the results are not perfect, do not take it for absolute truth.

**How does it works**

We count all the operations and sum the differences, nothing complicated here.
