# Stock Analysis

## Overview of Project
  The purpose of this project was to use VBA code to quickly analyze the stock market for a given year.  The code loops through a large stock market dataset for a given year and quickly summarizes the data to show the daily volume and return at the click of a button. 


## Results
  As you can quickly see in the results below, 2017 was a much better performing year with all but one stock(TERP) showing a positive return.  2018 was a challenging year where only two stocks showed a positive return.  Interestingly enough, those two stocks also had 2 of the highest three daily volumes.

  The exectution time for the non-refactored document was over 1 second for each year whereas the refactored code completed in about a 1/3 of the time.  Most people wouldn't notice the difference on this dataset; however, if you were to run it on the entire stock market or even 1000 tickers as opposed to 12 one would notice a significant difference in performance.
### Refactored Code Results:
  
![VBA_Challenge_2017](https://user-images.githubusercontent.com/90879042/135729647-c40f28a2-8434-4ac2-a80a-e177c15b528a.jpg)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/90879042/135729650-6773244c-bef7-4ae3-8a69-0d440ffe84dc.jpg)

### Original Code Results:
  
![Original Code 2017](https://user-images.githubusercontent.com/90879042/135730256-11b49451-c0a8-44df-8cbf-27dcc29e8e4d.jpg)
![Original Code 2018](https://user-images.githubusercontent.com/90879042/135730258-da6602fe-dc1c-4c89-923d-bd01cc9ac6aa.jpg)


  
 
## Summary
1. What are the advantages or disadvantages of refactoring code?

      The primary advantage of refactoring code is evident in this example - processing time.  The less time a user has to wait for a process to run, the more time they have for analyzing the results.  Another common component of refactoring is improving the code to make it easier for future users or even yourself to follow and understand.  Another benefit of the refactoring performed here is that the formatting logic was added to the same logic as the analysis resulting in one button click for a formatted report as opposed to two.
      One disadvatage of refactoring code would be the time it takes to refactor.  Not all refactoring attempts are going to result in better performance and if they don't, the benefit of the time spent is not there. 
 
 2. How do these pros and cons apply to refactoring the original VBA script?

     As mentioned above in the analysis, in this particular example the refactoring benefits are minimal, however if you expand the dataset to even 1,000 different tickers the benefits of refactoring would be significant and very well received by the end user.

