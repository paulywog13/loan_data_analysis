# loan_data_analysis


The goal of this independent project was to take loan data from LendingClub.com and analyze it to try and find trends in the data and to find the most profitable customers to lend to based upon the data. 

Data file used for this project is the loan_data.csv.

Dependencies used: Pandas, Seaborn, Matplotlib, Scipy.stats, and Numpy

I first used Jupyter Notebook to read in the csv file and then updated the column names and cleaned the data so it would be more simple to analyze. I didn't know what types of loans LendingCLub specialized in so the first graph I completed was an inventory of the Loan Types which showed that nearly a third of the loans in the file were debt consolidation loans. 

Based upon the multiple comparison graphs, debt consolidation loans look to be the most profitable due to the fact that they account for the highest number of loans, are middle of the pack in regards to both length of time outstanding and average loan outstanding balance, and have the second highest average interest rate. Small business loans have highest average balance and the highest average interest rate, have the 2nd longest average number of days, but only account for about 1/5 the number of loan volume as debt consolidation loans. 

![Comparison Bar Graphs](https://user-images.githubusercontent.com/69220393/131288744-1f3a31ed-bb02-47d8-9a36-41eb6955d78e.png)


