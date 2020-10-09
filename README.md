# Cancer-Drug-Test-Lab-Results
## CSV to Python. ETL & Matplotlib
### Function
The following data includes an animal study of mice and tumor growth given certain drug regimens. The goal with the data was to prove which drug regimens were successful in slowing or stopping tumor growth. 
Here I pull the CSV file into python and convert them to a data frame. Using the ETL process to clean up any null datapoints or mislabeled columns. 
I generated a technical report showing what drug regimen was successful and how successful it was compared to the others.  
### Organization
This code is organized in a Jupyter notebook and the data is within a separate folder. Each task is labeled and run in succession to ensure each element works independently. 
### How to Run
Open Jupyter notebook and make sure the data is in the correct file path. Pull in data, and ruin the different data frames. 
### Result
The number of tests by drug were between 175 and 225. Each mouse had an ID and were labeled male or female. The volume of the tumor was labeled next to a time stamp so you could track the growth over time. Capomulin was the most successful drug, showing an overall decrease to almost zero, of the tumor size. There was a statistical analysis done as well, for the average tumor size and mouse weight. This had an almost direct 1:1 correlation.<br/>
![image](https://github.com/mitchklee35/Cancer-Drug-Test-Lab-Results/blob/master/Pymaceuticals/images/cap_stat_analysis.PNG)<br/>
![image](https://github.com/mitchklee35/Cancer-Drug-Test-Lab-Results/blob/master/Pymaceuticals/images/final_tumor_vol.PNG)<br/>
![image](https://github.com/mitchklee35/Cancer-Drug-Test-Lab-Results/blob/master/Pymaceuticals/images/tests_per_drug.PNG)<br/>
