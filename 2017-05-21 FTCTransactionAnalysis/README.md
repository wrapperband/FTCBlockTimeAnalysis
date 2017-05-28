**Feathercoin - Feathercoin - Analysis of Block Time, Difficulty and Transactions quantity and values.**  

**Overview and Conclusions**

This analysis is a routine check of blockchain timings and activity. Over  48 Hours … from 19th to 21/5/2017

The average block time over 48hrs is good at 1:02

The charts are showing a positive increase in transactions / transaction values / amounts and baseline mining over the previous analysis.
The percentage of blocks with transactions has increase  to 50% of block. The transfer to fee rate is also higher at 371%


@wrapper 

The analysis is ongoing but the preliminary data analysis is on Github : 
https://github.com/wrapperband/FTCBlockTimeAnalysis/tree/master/2017-05-21%20FTCTransactionAnalysis  

*Feathercoin Block Analysis**

FTC is routinely analysed if there are any concerns. These analysis are stored on Github to use as templates or review historical analysis.

Values of the parameters analysed can be extracted from FTC debug file. The ABE software used to produce sites such as http://explorer.feathercoin.com/chain/Feathercoin?hi=1721682&count=1000 does some of this work for you, so for sporadic analysis of a few days it is convenient to scrape the data from there.
Normally the web site displays up to 100 blocks but this can be expanded manually.

The data is accumulated in a text document, then pasted into the spreadsheet template from the last analysis. Charts and calculations data ranges are corrected as required.

There were no suspicious time anomolies in the blockchain timings for the 50 hour test peroid. All 3 time anomalies were Blocks with the same time.



**Overview of the 50 Hour period up to 21/5/2017**

**FTC Fees over 48 Hours**  	223920	
**Transactions less fees**		83186838.30	
371 %	**Transaction to Fee ratio**	
**Percentage with Transaction**	51.00	
**Average Block Time 48hrs**    1:02 mins


**Temporal Anomalies** 

 
| Block       |     Time             |       Trans no.  |    Value           |          Diff      | CoinDaysDest  |  Time  |   TranTrue  |  TimeAnomaly |           
| ---------------- |  ----------------------------------------- |  ----------  |  -------------- |  ----------------- | ---------------------- |  ------------ |  --------- | ---------------- |
| 1724191   |    2017-05-21 10:02:52   |    2   |    216.05   |    9.83   |    12.42   |    00:57   |    1   |    
| 1724190   |    2017-05-21 10:01:55   |    1   |    80   |    9.837   |    0   |    00:00   |    0   |    1
| 1724189   |    2017-05-21 10:01:55   |    1   |    80   |    10.001   |    0   |    00:33   |    0   |    
|   |    |    |    |   |   |   |   |
| 1723314   |    2017-05-20 18:33:27   |    1   |    80   |    21.076   |    0   |    00:05   |    0   |    
| 1723313   |    2017-05-20 18:33:22   |    1   |    80   |    19.671   |    0   |    00:00   |    0   |    1
| 1723312   |    2017-05-20 18:33:22   |    1   |    80   |    18.359   |    0   |    00:08   |    0   |    
|   |    |    |    |   |   |   |   |
| 1722811   |    2017-05-20 10:03:41   |    2   |    25689.66   |    9.66   |    171.62   |    00:49   |    1   |    
| 1722810   |    2017-05-20 10:02:52   |    1   |    80   |    9.666   |    0   |    00:00   |    0   |    1
| 1722809   |    2017-05-20 10:02:52   |    1   |    80   |    9.666   |    0   |    00:15   |    0   |    



**Feathercoin Price charts**

Monitoring the FTC price chart on https://bitinfocharts.com/feathercoin/ , showed some anomalies with the Bitcoin to FTC price. The USD to BTC price had tracked up until recently and had divided, possibly due to a BTC price drop. That requires more in depth analysis as it may be due to trading in a third currency by the main exchanges. 

The expanding and high levels and novel variation prompted the analysis.

![Transaction Peak](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2017-05-21%20FTCTransactionAnalysis/FTCPrice_162139.png?raw=true)

 

**Feathercoin Difficulty**   

This chart shows the variation difficulty as the hash rate of different (coin switching)  pools is directed towards FTC. The red chart is seen to vary cyclically  at about 15 minutes.

The blue raising line is the block against time. The less variation in has, the straighter this line will be, so it is an indicator of how much the difficulty calculator (eHRC) is being stressed.

Comparing this to previous charts the average difficulty, and the rate and frequency of variation have increased. It looks like there are more switching pools forming some more complex time signature paterns. 


![Transaction Peak](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2017-05-21%20FTCTransactionAnalysis/2017-05-21-FTCDifficulty2Day.MediumTerm.jpg?raw=true)  
  
**Feathercoin Block Times**  

In this chart the green lines show the actual block times. In this case there was one high block times > 10 mins, and there were more block times > 8 mins than usually seen.

Comparing block time chart to the 25/10/2017, for instance, there seems to be a lot more 5:30 min blocks than usual. 

![Block Times ](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2017-05-21%20FTCTransactionAnalysis/2017-05-21-FTCBlockTimes2Day.MediumTerm.jpg?raw=true)    


**Feathercoin Number of Transactions**   

This chart shows the normal level of transactions, scaled down.
![Frequency of Transactions](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2017-05-21%20FTCTransactionAnalysis/2017-05-21-FTCTransactions2Day.MediumTerm.jpg?raw=true)  
 

**Feathercoin Value of Transactions**   

This scaled chart shows the value of transactions level. 

![Transaction value](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2017-05-21%20FTCTransactionAnalysis/2017-05-21-FTCValue2Day.MediumTerm.jpg?raw=true)



**Feathercoin Block Time Average 10 Blocks 21/05/2017**   

The average block time for the 50 hrs was normal.

![Block Time Average](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2017-05-21%20FTCTransactionAnalysis/2017-05-21-FTCBlockTimes2Day.10BlockAverage.jpg?raw=true)


