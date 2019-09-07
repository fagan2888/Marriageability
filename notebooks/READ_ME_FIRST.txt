There are 10 Jupyter notebooks associated with this project.  For replication of this project, each notebook should be used in the order listed below.  The first 4 notebooks were produced during the ingestion, wrangling and exploration phase of the project.  Notebooks 5 thru 10 include the code for various supervised machine learning algorithms used to predict the binary outcome and a final prediction notebook.
 A brief description of the ingestion, wrangling and exploration notebooks is provided below.

1. MarriagePerson-Ingest_Wrangle:  Includes the code to ingest and wrangle the ACS-2017 data file.  
2. MarriagePerson-Ingest_Wrangle _Pt2: Due to processing time, the team created a separate notebook to wrangle the “Occupation” feature used in the model.
3. MarraigeHouse-Ingest_Wrangle:
4. Marriage-EDA:  This notebook includes exploratory data analyses and feature transformation.


Five different classification algorithms were chosen for initial modeling, including Logistic Regression, K-Nearest Neighbor, Gaussian Naive Bayes, Gradient Boost, and Random Forest.  The notebooks are labelled accordingly.  

The file entitled “Marriage-Predictions” was used to generate predictions based on the final Logistic Regression algorithm.

Data Files
The data for this project is from the annual American Community Survey administered by the U.S. Census Bureau.  The specific data files are from the  2017 ACS 1-year collection.  The un-tabulated data files were downloaded from the ACS Public Use Microdata Sample (PUMS) online tool using the following link: https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml?refresh=t#.
The following .csv files were ingested as part of the persons/population and household data files: psam_pusa.csv, psam_pusb.csv, psam_husa.csv and psam_husb.csv.

Documentation
Technical documentation for the ACS collection and the 2017 1-year data is located on the following webpages:
* https://www.census.gov/programs-surveys/acs/data.html
* https://www.census.gov/programs-surveys/acs/technical-documentation.html
* https://www.census.gov/programs-surveys/acs/technical-documentation/pums/documentation.html
