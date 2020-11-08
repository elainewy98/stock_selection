# Indutry-specific stock selection model


- Data Set

1. factor_final_data.pkl

Data Type: dict

key: date (the date of the last trading day of each month)

value: the corresponding factors data of each period
	data format: dataframe/index: stock codes/columns: factors

2. train_set.csv 

3. test_set_combined.csv
Please refer to this as the final test set.

3.test_set.pkl 
The original file of test set data. Same format as factor_final_data.pkl


- Code Files

1. Data Wraggling.ipynb

Since our data were acquired through specific APIs provided by Joinquant, pleas run this ipynb file on www.joinquant.com under "研究环境". Otherwise data will not be accessed. 

In addition, when running the file, please avoid the "write pickle file" section which will cause around 1.5 hrs.

2. Models and Evaluations.ipynb

This ipynb file can be opened in normal jupyter notebook. 

Please put this file with test_set.pkl and train_set.csv under same folder address when opennig since it will write data.

![image](https://github.com/elainewy98/stock_selection/blob/main/backtest.png)





