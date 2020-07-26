
# Stock Analysis

## Overview of Project
The original purpose of this project was measuring each type of stock and their performance across a year. This is measured with the volume sold and yearly return in percentage. From there we refactored our code to run the same task and measure out performance against the original code to see if has improved.

### Results of Stock Data

Here we list the results of the stocks run for 2017 and 2018 using both the original and refactored code to show that the end result was the same data. Using color formatting for negative vs positive results on our return we can quickly see that stocks performed much better during the year 2017 than 2018. The only stock that performed better during 2018 was RUN.
Original Code Results       |  Refactored Code Results
:-------------------------:|:-------------------------:
![OriginalResult_2017](https://raw.githubusercontent.com/si1ver1/stock-analysis/master/Resources/originalResult_2017.jpg =300x)  |  ![RefactoredResult_2017](https://raw.githubusercontent.com/si1ver1/stock-analysis/master/Resources/refactoredResult_2017.jpg =300x)|
![OriginalResult_2017](https://raw.githubusercontent.com/si1ver1/stock-analysis/master/Resources/originalResult_2018.jpg =300x)  |![RefactoredResult_2017](https://raw.githubusercontent.com/si1ver1/stock-analysis/master/Resources/refactoredResult_2018.jpg =300x)


### Code Time Run Returned
Listed below are the results for our different code run times so we can easily verify which code ran quicker. We ran this for both data sets and also ran each one multiple times to verify consistency across the results. In every single instance the refactored code ran much quicker. We we average the results below we can see the original code usually runs in 0.66 seconds and the refactored code in 0.12 seconds or about 18% faster (100*0.12/0.66). This is more notable at longer run times. For example if we had a data set that took our original code 1 hour to complete: at 18% quicker our refactored code would finish it under 51 minutes. 
Original Code Time Run      |  Refactored Code Time Run
:-------------------------:|:-------------------------:
![OriginalResult_2017](https://raw.githubusercontent.com/si1ver1/stock-analysis/master/Resources/originalTime_2017.jpg =300x)  | ![RefactoredResult_2017](https://raw.githubusercontent.com/si1ver1/stock-analysis/master/Resources/refactoredTime_2017.jpg =300x)
| ![OriginalResult_2018](https://raw.githubusercontent.com/si1ver1/stock-analysis/master/Resources/originalTime_2018.jpg =300x) | ![RefactoredResult_2018](https://raw.githubusercontent.com/si1ver1/stock-analysis/master/Resources/refactoredTime_2018.jpg =300x)


### Summary
The advantage of refactoring code is that we can optimize it to run as efficiently and quickly as possible. This would be especially noticeable if our data set was larger and took longer to run. Another advantage is that we can re-use this optimized script for other data sets with some minor adjustments so we can more quickly gain benefits it in the future and if we were to expand our current code to run more calculations (such as across multiple years) this increased efficiency might already become relevant with smaller datasets.

The main downside to refactoring is the amount of time it takes to rewrite the code. In our example here both pieces of code run so quickly (in under a second) that optimizing it is not worth the amount of time it took us unless we plan on using much larger data sets in the future. Depending on the code the refactored code might be a little bit more difficult to understand.
