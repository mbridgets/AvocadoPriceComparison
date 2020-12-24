# TheMUGSSProject3

Our project looks at avocado sales throughout the United States between 2015 and 2018.  We obtained the avocado sales data from Kaggle.com which obtained the data through the Haas Avocado Board. We then used a second dataset from https://simplemaps.com/data/us-cities to add the latitude and longitude for each city to our avocado data to allow us to map our data.  We then added linear regression for 2018 to our dataset.  We cleaned and merged our data using Pandas.  All data-related files can be found in the data folder.

AWS Database Setup - Please follow the instructions in the AWSConnectionInstructions file to set up the AWS database via RDS, add the column names and add the csv used to load the database in AWS via S3.  You can begin with the CreateAWSDatabase.docx file to create the database, then use the AccessDBpgAdmin.docx file to access database via PGAdmin and create the table.  Finally, use the AWSFileStorage.docx file to add the csv file to AWS.

Loading AWS Database - We utilized the file named loading_AWS_database.ipynb to load the csv avo_data_withlr.csv to our AWS database.  

Once our database was loaded, we accessed the data via Tableau where we created the visualizations used on the webpage.  In addition to the data in our database, we also utilized the maps data included in Tableau for our analysis and visualizations.  We then saved the workbook through Tableau Public and incorperated the HTML from Tableau Public to our webpage.  
