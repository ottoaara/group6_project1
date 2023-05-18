# group6_project1
group project git repo for data source and cleaning.  
#main data file and import script for class group 6  project 1
# Author AO ottoaara@gmail.com. 952.693.1378 
# 5.5.23
# data source mpls open data https://opendata.minneapolismn.gov/datasets/cityoflakes::crime-data/explore?location=19.216823%2C-46.664577%2C4.00
# #CSV option under Crime Data Header
#The main.ipynb is the code file.  Please open using Juyptr notebook. 
# Read me file is this file 
# The MPLS Crime Trends Slide Deck is a pdf file containing our presentaion for the project. 


*The main data set is large. When navigating to the 
* Please note the file path variable is set to use a Data Folder on your desktop.  
* Please ensure you change your csv file path location if you save teh data set anywhere else.  
* 
* Please note when running the final version for presentation we will need to use data frame
* crime_data_main
part 1. - load
Loading requries going to the url above on line 6
First screen you will click download
Second screen you will choose CSV file. 
It will give you two options. 
    1. May 18th (or close to)
    2. Latest data avialable.  
    **Please note either option will have slightly more data then we had available to do the anlsysis so your data shouldn't be expected to match exactly if you run your ownr results. 

part 2. clean (removed all rows with null values)
In this section there is some clearning and sorting of data sets. Including datatype foramting to ensure we can do calculations on data sets
part 3. prep for analysis - created grouped and sub data sets exploring the high crime areas by crime time etc. : address and neighborhoods then counting violent crimes by type.  

**please note sorted version of each set immeidatly below them in code. 

#These are all the data sets built for ease of development.  Note the main file is large crime_data_main
# We have reduced the data set to violent crimes data frame clean_data_crime 


    
#crime_data_main  = full data set 15 Megs so seperated out into groups for ease of dev)
 
#crime_data_2019 = data for 2019 
#crime_data_2020 ...
#crime_data_2021 ...
#crime_data_2022...
##crime_data_2023 = data for 2023 

Data sets finnally were run using crime_data_main so they are ready for further analysis and visualizations. 

Thank you for reading through this plesae feel free to call me (Aaron) at 952 693 1378 with any questions. 
