# group6_project1
group project git repo for data source and cleaning.  
#main data file and import script for class group 6  project 1
# Author AO ottoaara@gmail.com. 952.693.1378 
# 5.5.23
# data source mpls open data https://opendata.minneapolismn.gov/datasets/cityoflakes::crime-data/explore?location=19.216823%2C-46.664577%2C4.00
# #CSV option under Crime Data Header
#The main data set is large. The file is in three main parts. 
* Please note due to size of main data set i have created a 1000 random row data set for ease of development
* ran_crime_data_df
* Please note when running the final version for presentation we will need to use data frame
* crime_data_clean
part 1. - load
part 2. clean (removed all rows with null values)
part 3. prep for analysis - created group by data sets grouping by address and neighborhoods then counting violent crimes by type.  
grouped_data_bydate
grouped_data_bylonglat 
**please note sorted version of each set immeidatly below them in code. 

#These are all the data sets built for ease of development.  Note the main file is large crime_data_main
# I have reduced the data set to violent crimes data frame clean_data_crime 
# Additionally for a corrleation puproses created two data sets 
#.  crime_data_bydata. - data sets by date they occurred
    crime_data_bylonglat- data sets by location.
    Please note each of these data sets have groupbys arleady done in code for you
    
#crime_data_main  = full data set (75 Megs so seperated out into groups for ease of dev)
#ran_crime_data_df is a light 1000 rows of data randomly choosen from crime_data_man to work with
#crime_data_2019 = data for 2019 
#crime_data_2020 ...
#crime_data_2021 ...
#crime_data_2022...
##crime_data_2023 = data for 2023 

Data sets finnally were run using crime_data_clean so they are ready for further analysis and visualizations. 
grouped_data_bydate
grouped_data_bylonglat 
