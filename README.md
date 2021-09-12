# Stock Analysis 

## VBA Challenge-Stock Analysis

### Analysing stocks for the years 2017 and 2018 for our client, Steve

The client (Steve) 
wants to perform Stock analysis at the click of a button. The initial analysis was for the single stock DAQO, which was then refactored to include all stocks.

Afterwards, the VBA code was further refactored to allow a faster run-time using loops

The document was formatted to allow easy reading 

The client also requested formatting of the document to include "ease of read" features. To accomodate this, conditional formatting was implemented to indicate positve and negative yearly performance.

## Results
Refactoring the original code allows us to run the code more efficiently and in vastly less time, approximately 0.8 seconds less. An advantage is that we used loops within loops to gather data faster, whick allowed data to be output faster. A disadvantage is the refactored code required a bit more work to master but turned out to me more efficient. It is ease to make a mistake with looping, but more can be done with less code.

Before the refactoring of the VBA Code, the runtimes were approximately 0.8 seconds higher:

![2017 initial analysis before the VBA Code was refactored](https://github.com/hmohabir/Stocks-analysis/blob/main/AllStocksAnalysis_2017.PNG)

![2018 initial analysis before the VBA Code was refactored](https://github.com/hmohabir/Stocks-analysis/blob/main/AllStocksAnalysis_2018.PNG)

After refactoring, the runtimes dropped significantly: 
![2017 Analysis showing a smaller runtime with refactored code](https://github.com/hmohabir/Stocks-analysis/blob/main/VBA_Challenge_2017.png)

![2018 Analysis showing a smaller runtime with refactored code](https://github.com/hmohabir/Stocks-analysis/blob/main/VBA_Challenge_2018.png)

The stocks that were successful in 2017 were ENPH and RUN. 
