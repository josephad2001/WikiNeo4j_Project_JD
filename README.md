# NeoWiki Project

This is a project for exploring the benefits of Wikipedia as a neo4j DB

Files:

DataGathered.xlsx
Page One: Log of number of links in paths
Page Two: The log of nodes and relationships during the import process
Page Three: Failed attempt at importing data

CleanXML.ipynb
This Code is used to take in each Part of the XML and remove non articles and articles

JsonToNeo.ipynb
This code is used to read JSON files and import the data into neo4j

Paths.ipynb
This code is used to generate two random articles. Find the shortest path. Then log how many steps it took

ScrapeIntoNeo4j.ipynb
This code uses web scraping to load wikipedia pages into a neo4j DB with relations between articles 

similarity.ipynb
This code measures the similarity of any two articles using the overlap coefficient 

SplittingData.ipynb
This code is used for processing the wikipedia xml dump into smaller sections