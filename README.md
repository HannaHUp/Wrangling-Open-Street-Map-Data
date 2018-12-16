# Wrangling-Open-Street-Map-Data

For Chinese version, see report.pdf document.

Choose any area in the world map using Openstreetmap.org and implement the process of data wrangling involving the process of gathering, assessing and cleaning the data. Use python programming skills to wrangle the data programmatically. Learn SQL and apply the provided schema to the project and perform analyses on the data.

Dataset
Map Area : Tianhe, Guangzhou, CHINA

I have been living in Guangzhou for more than a year.

Dataset extracted from Openstreetmap.org.
File size : 82.3 MB 

Project Setup
1. Sample data for Study 

2. Audit the Dataset :
Since the dataset was in raw xml format I wrote few scripts to audit the dataset so that, I can extract the meaningful information needed. I used xml.etree.cElementTree of python to traverse the data. Using this module I was able to extract the information from the nodes in the 'osm' file.

3. Processing the OSM file for data base 

4. Load the CSV files to the SQLite3 Database file :
After obtaining the csv files as per the schema I loaded them into a sqlite3 database file using the script create-sqlite3-database.py .

5. Data Analysis :
After the data is cleaned and loaded in to the database, I performed exploratory data analysis on the data to get some interesting findings. You can see my result report in report.pdf.


