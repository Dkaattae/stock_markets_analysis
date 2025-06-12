# week 2
## question 1, withdrawn IPO by company type
comment: acq corp has the most withdrawn values because most withdrawn companies are acq corp.    
maybe that is because most public traded companies are acq corp.    
further analysis needed, but we will need more data.

## question 2, median sharpe ratio or 2024 IPO company
comment: there are two companies that has no IPO price. that is because they changed ticker.   
changing ticker will impact huge on stock price but they are hard to track.    
as most data provider cares more about trading data instead of IPO.   
go to SEC edgar, find the company CIK, it will show prospectus of the company.   

## question 3, fixed months holdings stragegy   
comment: beta could be a factor, as returns should compared with index.   
insider lockin period is a factor here. also two month could release more information on what the company is doing.   

## question 4, simple RSI based trading strategy   
comment: package ta could be a problem.    
i am using pandas-ta instead.   
in google colab, 
first `!pip install numpy=1.24.4`,   
then `!pip install pandas-ta`,   
then `import pandas-ta`   
growth future 30d average is 86k   
growth future 5d average is 15k   

## question 5, predicting a positive return IPO   
see above comments, company ticker changing could be huge.   
