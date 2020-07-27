# VBA of Wall Street

## Overview of Project
### Purpose
Steve, a new finance graduate, is tasked with looking into DAQO stocks for his parents. He would also like to analyse a handful of other stocks to diversify their funds. He wants to compare two years’ worth of stock data, but, it would take a significant amount of time if it were done manually. Therefore, this project was completed to help Steve analyse a list of renewable energy stocks in addition to DAQO stock with only a click of a button. Using code to automate this analysis will allow Steve to analyse stock quickly and efficiently. He can also reuse it with any stocks in any year while reducing the chance of errors.

## Results
### Stock Analysis



The stocks in the analysis did relatively well in 2017. There was only one stock that had a negative return (TERP, -7.2%). All other stocks had positive returns. In 2018, majority of the stocks did badly. There were only two stocks that did well (ENPH and RUN, 81.9% and 84.0% respectively). The rest of the stocks had negative returns. Based on the analysis, DAQO stocks had overwhelmingly positive returns at 199.4% with about 35.8 million traded in 2017. In 2018, however, DAQO stocks took a plunge with a return of -62.6% with roughly 107.8 million traded. We can conclude from the analysis that stocks ENPH and RUN were successful with their returns on both years and therefore, would be a good choice to invest in.

### Code Analysis



In the original script, the codes ran in 0.7617188 seconds for 2017 and 0.7382813 seconds for 2018.



In the refactored script, the codes ran in 0.1210938 seconds for 2017 and 0.1171875 seconds for 2018. The refactored script ran about 6 times faster than the original script. This shows that refactoring the script improved code performance.



This was accomplished by making some minor changes to the original code. The refactored code only had to run once to deliver the analysis, while, the original code had to loop over the whole dataset for each ticker, resulting in 12 loops.

## Summary
As with all things, there are advantages and disadvantages of refactoring code. In general, refactoring code improves the performance of code, allowing the code to execute faster. It is also easier to maintain as the refactored code will be less complex and easier for another person to understand. However, there are also a lot of uncertainties when refactoring code and can get expensive as it can be very time consuming. Sometimes, it may even break the software due to the complexity of the code.
Even though refactoring the code for this analysis took quite some time, it ultimately helped the macro run much faster. Besides that, it can be reused in the future on any stock dataset for any year. Therefore, it is safe to say that the upfront cost of refactoring the code for this analysis was worth it.
