# stock-analysis

###Project Overview 
This project focused on refactoring previous VBA subroutines to optimize the performance of analyzing a spreadsheet of stock ticker outcomes for the years 2017 and 2018. Array structures were utilized in the refactored code to replace the additional steps required of the nested loop structure from the original algorithm. Output of ticker return was formatted to provide quick visual analysis of stocks with positive and negative annual returns.

###Results
The images illustrate the timed results of code optimization. It is easy to conclude that the usage of array structures, and single loop processing of these, performs more efficiently than the nested loop processing algorithm. It is also worth noting that the times for both years in the refactored algorithm are the same, suggesting a highly scalable linear relationship, while the difference in times for the more exponential relationship of the original code suggest this algorithm is not likely to scale as well for larger data sizes.
![2017 Original Algorithm](https://github.com/manBow1119/stock-analysis/blob/main/AllStocksAnalysis_Macro_2017.png)
![2018 Original Algorithm](https://github.com/manBow1119/stock-analysis/blob/main/AllStocksAnalysis_Macro_2018.png)
![2017 Refactored Algorithm](https://github.com/manBow1119/stock-analysis/blob/main/AllStocksAnalysisRefactored_Macro_2017.png)
![2018 Refactored Algorithm](https://github.com/manBow1119/stock-analysis/blob/main/AllStocksAnalysisRefactored_Macro_2018.png)

###Discussion about refactoring
Code refactoring, in general,  has some advantages and disadvantages. One advantage is improvements in efficiency of code. This becomes important as data sizes scale up considerably; more data, more steps. Another advantage to refactoring older code is to improve algorithmic thinking of the programmer, and the ability to generalize better algortihms to future projects. I felt like this project certainly highlighted each of these advantages. The usage of data structures like arrays requires less computational steps than the original nested loop. As a programmer I am likely to employ arrays and other collections over nested-loops, when it makes sense to do so. Conversely, one obvious disadvantage relates to the amount of time spent refactoring code compared to the amount of time actually saved. For example, this project's data size was relatively small, so the difference in algorithmic performance is somewhat neglible. Is it worth it to expend an extra 2 hours of work refactoring code to save half a second? For some projects this could mean that more money was spent on the work than was actually saved by the work done for a more elegant algorithm. 
