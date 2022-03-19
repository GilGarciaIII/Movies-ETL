# Movies-ETL
# Movies-ETL
This project was an introduction ot the EXTRACT, TRANSFORM, and LOAD process. Movie data from Wikipedia, Kaggle, and aggregated ratings was used to assemble a movie database from a clean dataset for a fictional hackathon.
ETL process was used to extract the Wikipedia and Kaggle data from their respective files
Cleaning the data and loding it correctly in SQL

## Overview
This analysis consists of four parts,this analysis is to create automated pipeline that extracts, transform and loads data.
Each step is building up from beginning of extracting data and function testing,and cleaning the data with the ETL process. 

##ETL_Function
- Data is extracted from the website in JSON and CSV formats.
- Data is transformed into Pandas data frames.
- JSON file requires extra step loading file first and then transforming into data frame.

##ETL_Clean_wiki_movies
-Clean the wiki movies data that was extracted. 
-Orginize the data into columes and and rows the data that is wanted with different methods.Opposed to the data that is not needed. 
-Apply the orginized and clean data. 

## ETL_clean_kaggle_data.ipynb

- Function extract_transform_load gets new tasks for cleaning Kaggle data and includes:
- Filling missing values and filtering unwanted columns.
- Merging data frames using pd_merge method.
- Changing datatypes, using methods pd.to_numeric, astype() and python comparison operators for Boolean types.


