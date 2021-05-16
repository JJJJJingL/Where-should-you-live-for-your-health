# Where Should You Live For Your Health
Authors: Melissa Collier, Norman Hong, Jingjing Lin Yeqing Liu, Xiner Ning, Arshia Singh  

In this project, we aim to investigate how your choice in residence may be impacting your health by exploring common data science techniques.

--------
Check the result directly? please click 👇

### ***************************  [Final Demo](http://arshia.georgetown.domains/ANLY501/Project.html)  ****************************
--------


## Datasets 
1. Water data 
2. Air quality data
3. Cancer rate  

## Potential analyses that can be conducted using the Data
From this data we want to investigate several questions, all under the umbrella  
question of: Is your health being impacted by where you live?  
What areas of the country offer the lowest chance of being diagnosed with any long-term health issues?  
Can we predict your chances of getting cancer based on where you live?  
Can we predict the chances of your child getting cancer based on where you live?  
Do your demographics (race, gender, etc) affect your ability to withstand negative health impacts from environmental factors?  
Does your income decrease your risk of getting cancer?  
Are certain environmental indicators highly correlated with particular health issues?  
Is the average household income of your county a predictor of the environment? Of the cancer rates?  
Does living near agricultural farms affect the quality of your water, and will this impact your health?  
What cities are going to kill you?  

## Files desciption
### Part 1: Access and load data, perform data cleaning 

1.	'All_Pollution_Data.csv', 'uncleaned_cancer.csv' and 'uncleaned_water.csv' are uncleaned csv files for air pollution, cancer and water quality datasets repectively.  
2.	The "airDataNewFeature.txt" file contains the entire uncleaned dataset as well as a new feature called "hasPM2.5".  
3.	'combined_datapull.py' includes all the python codes to investigate cleaniness of the three datasets.  
4.	This python script calls main() that includes several other functions, including general and customized functions.  
5.	General functions can be applied to all datasets are: checkType(), dataInfo(), nullCount() and get_Univalue().  
6.	.txt files 'Air_data_analysis.txt', 'Cancer_data_analysis.txt' and 'Water_data_analysis.txt' are generated by calling the above general functions.  
7.	main() also has customized functions for water and air datasets.  
8.	functions that print results to the console: stateCountyChecker(a,b), waterClean(data)  
9.	function that generate 'waterCheck.txt': waterClean(data)  


### Part 2: (1)Finalizing Data Cleaning (2)EDA:Means, Medians or Modes for 10 attributes (3)Histograms and Correlations (4)Cluster Analysis (5)Hypothesis Testing  
1. 'cleaned_cancer.csv', 'cleanPollutionData.csv' and 'water_clean.csv' are cleaned csv files for air pollution, cancer and water quality datasets repectively.  
2. 'Project_2_cleaning_code.py' includes the clean methods.  
3. 'Project_2_analysis_code.py' includes the analysis methods.  


### Part 3:  
Our final story is contained in a website url: [Final Demo](http://arshia.georgetown.domains/ANLY501/Project.html) 






