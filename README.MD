# Green Stocks Analysis  

## Overview of Project  
A recent finance graduate, Steve, wants to help his parents determine how to invest in green stocks, Steve's parents want to invest into DAQO New Energy Corp "DQ" a stock that reminds them of how they met at Dairy Queen many years ago, Steve wants to analyze other green energy stocks in addition to DAQO to get a better picture of the green energy sector and create a stronger portfolio for his parents, an analytical approach, with the performance of others green stocks in 2017 and 2018 he wants to evaluate which stocks may produce better return for his parents.  

## Results  
### 2017 vs 2018 Stock Performance

By looking at the images below it is clear that in 2017 the green stocks performed better than in 2018 being DQ, ENPH and SEDG the ones with best returns in 2017, the returns in 2018 were not so positive with only ENPH and RUN on positive returns, ENPH and RUN are the only two stocks to consistently be in the green in 2017 and 2018, in my opinion Steve should look into ENPH and RUN instead of DQ as promising investments, certainly with ENPH stocks as it has the most favorable years.  

![allStocks2017and2018](https://user-images.githubusercontent.com/16723095/121767362-5e35b400-cb1d-11eb-8b5a-d5ea2c63233a.png)

### Execution times  
original script  
![executionTimeNoRefactor](https://user-images.githubusercontent.com/16723095/121767366-67268580-cb1d-11eb-9a95-9604d3f81316.png)

refactored script  
![executionTimeRefactored](https://user-images.githubusercontent.com/16723095/121767372-6aba0c80-cb1d-11eb-847e-bc30fe7042de.png)

## Summary     
### What are the advantages or disadvantages of refactoring code?   
  
Refactoring code makes easier to underestand the final product, after refactoring the output execution is faster, however, refactoring code is a time-consuming operation that depend on the length and complexity of the code and in the proccess of refactoring some new bugs might appears too.  

### How do these pros and cons apply to refactoring the original VBA script?    

In this case the refactoring proccess makes a reading of all the data in only one pass, in comparison with the no refactored code that cicle the whole data for every ticket, instead of running two loops to access the tickers and data now we use only one loop for this operation.  
