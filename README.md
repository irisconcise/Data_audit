# Data_audit
Auditing data for data science projects

# __Data Audit Code__

### i) Data Audit Table
- This workbook contains code to audit excel data files
- By opening a 'csv' file and running the below code, each function will return a dataframe that can be pasted into a document. 
- 1) __data_audit__ The first function will create a dataframe that detects missing values for each column
- 2) __value_count__ This function returns a series containting counts of unqiue values for each column
- 3) __join_tables__ Returns an inner join of the two dataframes produced above

### ii) Deleting Missing Values 
- This section can be used for deleting incomplete data in dataframes
- 1) __missing_values_table__ craetes a data for missing data only 
- 2) __remove_incomplete_columns__ The code runs the missing values table and removes the columns which contain more than x% of missing data
### _For R users (& Python beginners)_
Copy whole script and paste into JupyterLab or JupyterNotebook.
Change the read_csv argument to your chosen excel csv file.
Select all script and press play.
The Data audit table will be copied to a clipboard and can then just be pasted to an alternative source.
