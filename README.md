# Movies-ETL.
Initial repo construction

## Summary
Welcome to the Extract-Transform-Load(ETL) script.  This script is designed to bring together data about movies from Wikipedia and Kaggle and to prepare them for you to analyze!  To download the most recent versions of the data files that this code was built to accomodate, click on the links below:
* [Wikipedia](https://courses.bootcampspot.com/courses/166/files/37152/download?wrap=1)
* [The Kaggle User Community](https://www.kaggle.com/rounakbanik/the-movies-dataset/download)

When the three required files are loaded, this script:
  1. Creates an ETL pipeline from raw data to a SQL database.
  2. Extract data from three separate files using Python.
  3. Cleans and transforms the data to improve quality, versatility and usability using Pandas.
  4. Loads the data with PostgreSQL to create an easy to manipulate database.

In order to run this script, you will need three files: 
* From Wiki: 
  * wikipedia.movies.json
* From Kaggle: 
  * movies_metadata.csv
  * ratings.csv

![View the code here.](/Challenge.py)

Last Updated: May 6, 2020
