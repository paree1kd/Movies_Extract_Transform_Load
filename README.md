## Movies - Extracting, Transforming, and Loading

### Amazon Prime is asking for an automated pipeline that is able to take in incoming data and perform appropriate transformations to be loaded into existing tables. A function will be created that would be able to take three files and perform the ETL process and add it to a PostgreSQL database.

### Results
#### First part of the project requires the development of DataFrames that took in the three files:
* movies_database.csv
* ratings_small.csv
* wikipedia-movies.json

#### Second part of the project needed Python, Pandas, ETL, and refactoring code. The wikipedia dataset was extracted and used to be used with the Kaggle dataset provided. To catch duplicates and errors, a try-except was implemented into the code, decreasing the wiki movies data frame to 193 columns to 21.

#### Third part of the project utilized Pandas, Python, ETL, and refactored code and extracted Kaggle metadata and MovieLens rating data and put into the wikipedia dataset in a merged dataset; a try-expect was added to catch duplicates and errors like in the second part of this project.

#### Finally, last part of the project included the addition of PostgreSQL to create the movies_df and MovieLens rating data into the SQL database. By connecting to the PostgreSQL, two datasets with a large count amount for each resulted with pictures below.

![movies_query](https://user-images.githubusercontent.com/102098068/168531763-81da5bd6-b226-42c8-b6da-f05e1d035b97.png)

![ratings_query](https://user-images.githubusercontent.com/102098068/168531765-95476339-28af-4f83-adb3-a773d414841a.png)
