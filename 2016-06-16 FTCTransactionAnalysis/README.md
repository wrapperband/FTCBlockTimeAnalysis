# FTC Block Time Analysis due to increase in Hash Rate 16/06/2016

@wrapper I've  updated my Blockchain analysis with 30 Hours up to 12:00 last night due to an increase in Hash on p2pool, to see the effect.

The analysis uses feathercoin blockchain explorer to output 1800 records, which are copied into text editor to remove html, then into a template spreadsheet.

http://explorer.feathercoin.com/chain/Feathercoin

https://github.com/wrapperband/FTCBlockTimeAnalysis

The main change I noted on the 16th June 2016 was an increase in Percentage of Blocks with more than one transaction. I therefore added a new chart to show the number of transactions per block, which I will gradually backport to the other days analysis.

https://github.com/wrapperband/FTCBlockTimeAnalysis/tree/master/2016-06-16%20FTCTransactionAnalysis

The spreadsheet is currently set up to chart the 100 blocks i.e. 100 mins or ~ 1Hr   directly in the past of the sample time. The medium term shows 1800 mins or 30 Hrs. 

Note : the analysis for the 20/5/2016 peak was 2900 mins as that was to see why the FTC day difficulty was so high.

This is the 3 month chart from http://cryptocoinstats.com/coinsummarydetail.php?ac=FTC

Note : Need to extend the 20th 05 analysis back to 19th to cover the peak difficulty day.

**FTC 3 months Daily Difficulty 16-06-2016**
![FTC 3 month Block Difficulty 16-06-2016](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2016-06-16%20FTCTransactionAnalysis/FeathercoinHashRate3Months2016-06-Cryptoconstats.com.jpg?raw=true)  

Note : All difficulty and therefore Hash rate calculations are averages. In previous analysis it is possible to poll Feathercoind and find what the difficulty would have been for an average over any number of blocks. i.e. It is possible to post calculate and check wither a "coin information site" has accurate day average calculation..

Note : The diagonal blue line shows how stable the 1 minute block time is,  straighter = good  , wobbles = time changes.

**FTC Transactions Per Block over 100 Blocks 16-06-2016**
![FTC Transactions Per Block 16-06-2016](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2016-06-16%20FTCTransactionAnalysis/2016-06-16-FTCTransactionsPerBlock24Hr.MediumTerm.jpg?raw=true)  

Note : The red line shows the average number of transactions, ~ 2.2 per block, which needs more investigating, but superficially similar to previous a results. To do :  Back Port Average transactions per block reading, extra chart average Transactions per 10 Blocks.

**FTC Transactions Per Block over 1 Day 16-06-2016**
![FTC Transactions Per Block 16-06-2016](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2016-06-16%20FTCTransactionAnalysis/2016-06-16-FTCTransactionsPerBlock100Hr.ShortTerm.jpg?raw=true)  

Note :  There are larger and more frequent hash variations than normal, high hash triggered the analysis.
The re line shows how the additional hash rate is driving up the average difficulty, as well as handle the hash variations.

**FTC Difficulty over 100 blocks 16-06-2016**
![FTC 100 Block Difficulty 16-06-2016](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2016-06-16%20FTCTransactionAnalysis/2016-06-16-FTCBlockDifficulty100Hr.ShortTerm.jpg?raw=true)  

**FTC Difficulty over 1 Day blocks 16-06-2016**
![FTC 100 Block Difficulty 16-06-2016](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2016-06-16%20FTCTransactionAnalysis/2016-06-16-FTCBlockDifficulty24Hr.MediumTerm.jpg?raw=true)  

**FTC Block time 100 Blocks 16-06-2016**
![FTC 100 Block Difficulty 16-06-2016](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2016-06-16%20FTCTransactionAnalysis/2016-06-16-FTCBlockTime100Hr.ShortTerm.jpg?raw=true)  

**FTC Block time 1 Day 16-06-2016**
![FTC 100 Block Difficulty 16-06-2016](https://github.com/wrapperband/FTCBlockTimeAnalysis/blob/master/2016-06-16%20FTCTransactionAnalysis/2016-06-06-FTCBlockTime24Hr.MediumTerm.jpg?raw=true)  

