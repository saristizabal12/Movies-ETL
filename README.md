# Movies-ETL
Extract, Transform, and Load to create a Data pipeline with AWS. Using Python, Pandas, Jupyter Notebook, and PostgreSQL

## Overview:
In this project we are using kaggle Movie data to extract.csv files and json files, then transform them, and load to PostgreSQL using Python.

### Deliverable 1: Write an ETL function to read three data files
In deliverable one we created a function to read 3 seperate files
We later open the Wikipedia JSON file and use the json.load() function to convert the JSON data to raw data.

### We used the data to create 3 data frames:

#### Image below is the Data Frame for

#### Image below is the Data Frame for

#### Image below is the Data Frame for


Then use the variables provided to create a path to the Wikipedia data, the Kaggle metadata, and the MovieLens rating data files.

Lastly, we set the DataFrames from the return statement equal to the files. Then reassigning the variables created to return the statement.


### Deliverable 2: Extract and Transform the Wikipedia Data
We used Python, Pandas, and the ETL process, to refactor code, extract and transform the Wikipedia data so we can merge it with the Kaggle metadata. 




Once that was set, we exxtracted the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors
### Deliverable 3: Extract and Transform the Kaggle Data

Next step was to, extract and transform the Kaggle metadata and MovieLens rating data.
Convert the transformed data into separate DataFrames. 
Merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame
Lastly, we merged the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.
### Deliverable 4: Create the Movie Database
Finally we added the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
