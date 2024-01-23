# Website_Metadata_Scraping
Script to extract all holiday metadata from GreatRailJourneys.com to compile a database

I used the html structure of the tours page, once fully loaded, to identify the features by html style and extract them. The extracted tour urls are then used within a loop to extract additional information from the individual tour pages.
The features are then cleaned, processed, export to a csv file and some preliminary EDA conducted.
