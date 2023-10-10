# Data Curation and Analysis
Project Goal:

The goal of this project is to curate data by extracting, transforming, loading, plotting, visualizing, and analyzing data on cities in the United Kingdom (UK) from the Wikipedia page "List of cities in the United Kingdom" and performing data visualization and analysis.

For data curation, I specifically extracted and cleaned data from the Wikipedia page to create a structured dataset of UK cities, including attributes like Image,	City,	Year granted or confirmed,	City council status,	Nation/region	City, Population. I took out the image becauseit could not be seen anyways, was irrelevant and unnecessary to the project, and not transferrable.

For visualizing the curated data, I wanted to gain insights into the population distribution among UK cities. The best graph to visualize the data is a bar graph for compasion because it is not a trend but rather comparing population between cities. The bar chart also helps me understand the difference in population in UK cities from highest to lowest populations.

Data Sources:

"List of cities in the United Kingdom," accessed at https://en.wikipedia.org/wiki/List_of_cities_in_the_United_Kingdom.

License:

The data extracted from Wikipedia is available under the Creative Commons Attribution-ShareAlike License (CC BY-SA). 
Creative Commons Corporation ("Creative Commons") is not a law firm and does not provide legal services or legal advice. By exercising the Licensed Rights (defined below), You accept and agree to be bound by the terms and conditions of this Creative Commons Attribution-ShareAlike 4.0 International Public License ("Public License"). To the extent this Public License may be interpreted as a contract, You are granted the Licensed Rights in consideration of Your acceptance of these terms and conditions, and the Licensor grants You such rights in consideration of benefits the Licensor receives from making the Licensed Material available under these terms and conditions.enefits the Licensor receives from making the Licensed Material available under these terms and conditions.

Data Attributes:

The dataset consists of the following attributes:

Image (taken out): Image of the United Kingdom city. 
City: (string object) The name of the city in the United Kingdom.
Year granted or confirmed: (string object): Year at the time.
City council status: (string object) 
Nation/region: (string object) The administrative region or area where the city is located (e.g., England, Scotland, Wales, or Northern Ireland).
City Population: (float) The population of the city at a specific point in time.

Known issues:
Data can be inaccurate on Wikipedia pages since it can be edited by any user, and the data is not always up-to-date or accurate in general. It's important to verify the data and cross-reference it with reliable sources.
The Wikipedia page may have specific criteria for including cities which means that some towns or settlements may be excluded.

To address these potential issues, it's important to carefully validate and clean the data, consider the data's source, and be aware of its limitations when performing analysis and visualization.

