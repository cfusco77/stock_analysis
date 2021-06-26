# Stock Analysis

## Overview of Project
Perform analysis using a dataset of 12 green energy stocks to uncover any hidden trends

### Background 
Steve just graduated with a finance degree and his parents have asked him to advise on their future investments. Steve's parents have a passion for green energy but know little of how to interpret the stock market. They were moved by the mission of DQ New Energy but did little research into whether it was a sound investment. Steve, with our help, is going to look into the financial return for DQ, in addtion to a few alternate stocks, and make his parents a recommendation. 

### Methods 
Steve chose 11 stocks in addtion to DQ for his analysis. Together we rendered an output that shows for every stock the Total Daily Volume and Return on Investment. Positive returns are color coded green while negative returns are marked red. We produced the same chart over the span of two years, 2017 and 2018, to help identify any trends in the market. 

## Results
All but one of our chosen stocks (TERP) saw positive returns in 2017. While this is not an all encompassing list of green energy providers, it might be fair to say that the renewable energy market was booming in 2017. DQ, Steve's parent chosen stock, did exceptionally well, 199.4% return. 
However in 2018, all but two stocks saw negative returns. While ENPH and RUN saw continued growth YOY, DQ saw a -62.6% return. 

### Next Steps
Now, to do a little more research for his parents, Steve wants to expand the dataset to include the entire stock market over the last few years. Although our code works well for a dozen stocks, it might not work as well for thousands of stocks. And if it does, it may take a long time to execute.
To aid in future analysis, we have refactored the code.  

### Why Refactor Code?
Refactoring code increases efficiency by taking fewer steps, using less memory, or improving the logic of the code to make it easier for future users to read. 
For our initial code we created a timer to track how long it takes the code to execute. For 2017 and 2018 the code ran for .51 and .52 seconds respectively. The screenshots below illustrate that refactoring the code brought the runtime down to .09 seconds. 
 
![VBA_Challenege_2017](https://github.com/cfusco77/stock_analysis/blob/main/Resources/VBA_Challenege_2017.png)
![VBA_Challenege_2018](https://github.com/cfusco77/stock_analysis/blob/main/Resources/VBA_Challenege_2018.png) 

In addtion we have rewritten the code such that it loops through the data one time collecting all the necessary information, this could easily we expanded out to include additonal stocks.

### What are the Drawbacks of Refactoring Code?
Code refacatoring is time consuming and you may introduce bugs or broken functionality into your code which takes time to diagnose and correct for. Code refactoring requires additonal sophistication in logic and may be hard for someone else reading through your project to detect what is going on. To remedy the latter I have provided ample comments throughout my code. 

 
