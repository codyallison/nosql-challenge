# nosql-challenge
module 12 homework assignment

Hello!

This repository is for Washington University Data Analytics Bootcome Module 12 homework assignment 'nosql-challenge'
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. the code provided hopes to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

in this repository you will find a few key documents for your use.

In the 'Starter Code' folder you will find a file 'NoSQL_setup_starter.ipynb'
In this file, you will find reference to a 'establishments.json' document located in the 'Resources' folder. run the mongoimport comand within your powershell in order to create the database and collection. 
-After that you are free to use the code. Next, you will see examples of how documents in the database are structured. we continue on to add a new establishment, validate and correct missing information, and convert datatype where appropriate. Lastly, we delete establishments located in Dover as the magazine is not interested in these establishments

Next in the 'Starter Code' Folder you will find the next file 'NoSQL_analysis_starter.ipynb'
In this file we conduct a few analysis based on various criteria such as the following:
-establishments with hygieve score of 20, we display a document example as well as a dataframe preview
-establishments with rating value of 4 or greater with a local authority in London. displayed as document and dataframe
-top 5 establishments with rating value of 5 sorted by hygiene score located nearest the establishment we added in part 1
-number of establishments with hygiene score of 0, grouped by local authority


Code written by Cody Allison for Washington Univeristy bootcamp

References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
