# Movies ETL

## Overview
In this project I took in the data from the three resources provided, performed transformations on it using the previous code and loaded the data into existing tables in PostgreSQL.  The difference here? I created a function extract_transform_load() that took in three parameters (wiki_file, kaggle_file and ratings_file) to expedite the ETL process, allowing the good folks at Amazing Prime to be able to update the data on a daily basis.
